pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://your-repo-url.git'
            }
        }
        stage('Build Docker Image') {
            steps {
                script {
                    sh 'docker build -t my-web-app .'
                }
            }
        }
        stage('Run Docker Container') {
            steps {
                script {
                    sh 'docker run -d -p 80:80 --name web-app my-web-app'
                }
            }
        }
    }
}
