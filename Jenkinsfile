pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Jenkins automatically checks out SCM, so no need for extra git command
                echo 'Repository checked out automatically done by Mahudesh.'
            }
        }

        stage('Setup Python') {
            steps {
                // Ensure Python3 is installed and available
                sh 'python3 --version'
            }
        }

        stage('Run Python Script') {
            steps {
                echo 'Running hello.py...'
                sh 'python3 hello.py'
            }
        }
    }
}
