pipeline {
    agent {
        docker {
            image 'docker:dind'
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
