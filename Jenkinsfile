pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                bat 'gradle clean assemble'
            }
        }
        stage('Test') {
            steps {
                bat 'gradle test'
            }
            post {
                always {
                    junit 'build/test-results/test/*.xml'
                }
            }
        }
    }
}