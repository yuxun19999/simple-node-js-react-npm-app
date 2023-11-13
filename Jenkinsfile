pipeline {
    agent {
        docker {
            image 'e17f59bba84bce6ef89222590569feb6b743f5560d22b7501281082e6ceb40ff'
            args '-p 3000:3000'
            reuseNode true
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
