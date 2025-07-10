pipeline {
    agent { 
        docker { 
            image 'python:3.13.5-alpine3.22'
            abel 'agent_docker'
        } 
    }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
