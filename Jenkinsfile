pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                // Checkout your source code repository
                script {
                    checkout scm
                }
            }
        stage('Build') {
            steps {
              echo "test1"
                
            }
        }
        stage('Test'){
            steps {
                echo "test2"
                
            }
        }
        stage('Deploy') {
            steps {
               echo "test3"
            }
        }
    }
}
