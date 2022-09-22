pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Hello world!"
            }
        }
        stage('Cat README') {
            when {
                branch "fix-*"
            }
            steps {
                echo "cat README.md"
            }
        }
    }
}
