pipeline {
    agent { 
      docker { 
        image 'php:8.4.8-alpine3.22'
        label 'agent_docker'
      } 
    }
    stages {
        stage('Verification') {
            steps {
                sh 'php --version'
            }
        }
    }
}
