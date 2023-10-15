pipeline {
    agent {
        docker {
            image 'node:16'
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

