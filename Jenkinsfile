pipeline {
    agent any
    
    environment {
        APP_PORT = '9090'
    }
    
    stages {
        stage('Build') {
            steps {
                sh 'mvn package'
            }
        }
        stage('Unit Test') {
            steps {
                sh 'mvn test'
            }
        }
    }
}

