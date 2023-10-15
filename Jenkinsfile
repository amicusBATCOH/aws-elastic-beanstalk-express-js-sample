pipeline {
    agent {
        docker {
            image 'dind'
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

