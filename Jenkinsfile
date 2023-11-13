pipeline {
    agent {
        docker {
            image 'node:20.9.0-alpine3.18'
            args '-p 8080:8080'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}
