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
                sh 'cd auth && npm run test:ci'
            }
        }        
    }
}