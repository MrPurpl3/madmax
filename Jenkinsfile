pipeline {
    agent any

    stages {
        stage('cicd') {
            steps {
                free -m;df -h;echo 3
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
