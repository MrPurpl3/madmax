pipeline {
    agent any

    stages {
        stage('cicd') {
            steps {
                free -m
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
