pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/himanic72538/a4_q8_docker-build.git'
            }
        }
        stage('Display Message') {
            steps {
                echo 'Build executed successfully from Jenkinsfile!'
            }
        }
    }
}
