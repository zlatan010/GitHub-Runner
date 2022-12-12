pipeline {
    agent {
        docker {
            image 'kasmweb/postman'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'postman --version'
            }
        }
    }
}
