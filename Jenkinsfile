pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Mahudesh/Jenkins_Deployment.git'
            }
        }
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
        stage('Run') {
            steps {
                sh 'npm start'
            }
        }
    }
}
