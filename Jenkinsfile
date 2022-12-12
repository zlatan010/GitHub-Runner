pipeline {
    agent {
        docker {
            image 'kasmweb/postman:1.12.0'
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
