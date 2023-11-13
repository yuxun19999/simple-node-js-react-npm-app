pipeline {
    agent {
        docker {
            image 'node:20.9.0-alpine3.18'
            args '-p 5000:5000'
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
