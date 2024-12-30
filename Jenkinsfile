pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/hasham888/30dec.git'
            }
        }
        // Other stages like Build, Test, Deploy
    }
}
