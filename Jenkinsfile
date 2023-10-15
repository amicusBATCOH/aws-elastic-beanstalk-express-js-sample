pipeline {
    agent {
        docker {
            image 'docker:dind'
            args '-v /var/run/docker.sock:/var/run/docker.sock'
        }
    }
    
    stages {
        stage('Check Docker Version') {
            steps {
                sh 'docker --version'
            }
        }
        
        stage('Build') {
            steps {
                sh 'npm install --save'
            }
        }
    }
}

