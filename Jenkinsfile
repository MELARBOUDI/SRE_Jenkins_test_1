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
    stage('Install Composer') {
            steps {
                script {
                    // Commandes pour installer Composer
                    sh 'apt-get update && apt-get install -y curl unzip && curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer'
                }
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
