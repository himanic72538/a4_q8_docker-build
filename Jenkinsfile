pipeline {
    agent any
    stages {
        stage('Checkout Code') {
            steps {
                git 'https://github.com/himanic72538/a4_q8_docker-build.git'
            }
        }
        stage('Build Docker Image') {
            steps {
                sh 'docker build -t my-flask-app .'
            }
        }
    }
}
