pipeline {
    agent {
        docker {
            image 'docker:dind'
			args '--insecure-registry dind:2376'
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

