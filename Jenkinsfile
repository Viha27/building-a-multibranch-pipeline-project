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
                branch "dev-*"
            }
            steps {
                echo "CAT README.md"
            }
        }
    }
}
