pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/yur-ochka/lab4-it-projects'
            }
        }

        stage('Build') {
            steps {
                sh 'gcc main.c -o main'
            }
        }

        stage('Test') {
            steps {
                sh './main'
            }
        }
    }
}