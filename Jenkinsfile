pipeline {
    agent { 
        docker { 
            image 'python:3.13.5-alpine3.22'
            label 'agent_docker'
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
