pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                sh 'ls'
                sh 'touch sample.txt'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'pwd'
                sh 'ls build/'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
            }
        }
    }
}
