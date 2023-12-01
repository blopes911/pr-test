pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                sh 'python3 test.py'
            }
        }
        
        stage('Test') {
            steps {
                // Add your test steps here
                // For example: sh 'mvn test'
            }
        }
        
        stage('Deploy') {
            steps {
                // Add your deployment steps here
                // For example: sh 'mvn deploy'
            }
        }
    }
}
