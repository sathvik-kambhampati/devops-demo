pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                echo 'Cloning repository...'
            }
        }

        stage('Build') {
            steps {
                echo 'Building application...'
                sh 'python3 --version'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'echo "Tests passed"'
            }
        }

        stage('Run App') {
            steps {
                echo 'Running app...'
                sh 'python3 app.py'
            }
        }
    }
}
