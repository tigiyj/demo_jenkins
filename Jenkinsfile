pipeline {
    agent { 
        docker {
            image 'php:7-alpine'
        } 
    }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}