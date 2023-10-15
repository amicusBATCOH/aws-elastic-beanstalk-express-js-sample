pipeline {
    agent {
        docker {
            image 'dind2'
        }
    }
    
    stages {
        stage('Build') {
            steps {
                sh 'npm install --save'
            }
        }
    }
}

