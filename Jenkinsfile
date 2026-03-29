pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/yur-ochka/lab4-it-projects.git'
            }
        }

        stage('Build') {
            steps {
                bat 'node -v'
            }
        }

        stage('Test') {
            steps {
                bat 'node test.js'
            }
        }
    }
}