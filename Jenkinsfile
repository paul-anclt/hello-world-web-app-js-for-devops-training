pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Building') {
            steps {
                echo 'Building....'
            }
        }
        stage('Push on docker hub') {
            steps {
                echo 'Pushing....'
            }
        }
        stage('Deploy PPROD') {
            steps {
                echo 'Deploying PPROD....'
            }
        }
        stage('Test PPROD') {
            steps {
                echo 'Testing PPROD....'
            }
        }
        stage('Deploy PROD') {
            steps {
                echo 'Deploying PROD....'
            }
        }
        stage('Test PROD') {
            steps {
                echo 'Testing PROD....'
            }
        }
    }
}