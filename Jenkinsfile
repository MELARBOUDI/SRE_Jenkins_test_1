pipeline {
    agent { 
      docker { 
        image 'php:8.4.8-alpine3.22' 
      } 
    }
    stages {
        stage('Verification Version') {
            steps {
                sh 'php --version'
            }
        }
    }
}
