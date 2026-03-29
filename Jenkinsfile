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
                bat 'echo Build stage completed successfully'
            }
        }

        stage('Test') {
            steps {
                bat 'echo CI/CD works!'
            }
        }
    }
}