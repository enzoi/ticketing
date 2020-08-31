pipeline {
    agent any
    stages {
        stage('Build-auth') {
            steps {
                sh 'cd auth && npm install'
            }
        }
        stage('Test-auth') {
            steps {
                sh 'npm run test:ci'
            }
        }        
    }
}