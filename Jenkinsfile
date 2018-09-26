pipeline {
    agent any

    stages {
        stage('cicd') {
            steps {
                sh 'free -m;df -h'
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
