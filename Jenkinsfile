pipeline {
    agent {
        docker {
            image 'grafana/jmeter-to-k6'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'jmeter --version'
            }
        }
    }
}
