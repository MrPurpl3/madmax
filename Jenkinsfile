#test

pipeline {
    agent any

    stages {
        stage('cicd') {
            steps {
                docker-node(image: 'cloudbees/jnlp-slave-with-java-build-tools') {
    git 'https://github.com/jglick/simple-maven-project-with-tests'
    withMaven {
        sh 'mvn install'
    }
}
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
