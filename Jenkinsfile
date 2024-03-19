pipeline {
    agent any
    
    environment {
        APP_PORT = '9092'
    }
    
    stages {
        stage('Build') {
            steps {
                sh 'mvn packagesa'
            }
        }
        stage('Unit Test') {
            steps {
                sh 'mvn test'
            }
        }
    }
}

