pipeline {
    agent {
        docker {
            image 'python:3.12.5-alpine3.20'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'python --version'
            }
        }
    }
}