pipeline {
    agent {
        docker {
            image 'node:16'
        }
    }
    
        stage('Build') {
            steps {
                sh 'npm install --save'
            }
        }
    }
}

