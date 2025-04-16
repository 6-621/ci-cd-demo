pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                sh 'echo Hello from Build stage'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'echo Simulated tests passed!'
            }
        }
    }
}