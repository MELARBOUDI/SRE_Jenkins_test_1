pipeline {
    agent {
      node {
        label 'agent_docker'
      }
      docker { 
        image 'php:8.4.8-alpine3.22'
      } 
    }
    stages {
        stage('Verification') {
            steps {
                sh 'php --version'
            }
        }
    stage('Compos install') {
            steps {
                //sh 'composer install'
                sh 'php --version'
            }
        }
    stage('TEST') {
            steps {
                //sh 'vendor/bin/phpunit'
                sh 'php --version'
            }
        }
    }
}
