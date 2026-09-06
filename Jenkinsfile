pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out code from GitHub...'
            }
        }
        stage('Build') {
            steps {
                echo 'Building application artifacts...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running automated test suites...'
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Deploying application to staging environment...'
            }
        }
    }
}
