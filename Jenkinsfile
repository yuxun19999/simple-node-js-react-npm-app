pipeline {
    agent {
        docker {
            image 'node:20.9.0-alpine3.18' 
            args '-p 3000:3000' 
            reuseNode true
            registryUrl 'https://index.docker.io/v1/'
            customWorkspace '/Users/yuxun/Documents/GitHub/simple-node-js-react-npm-app'
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
