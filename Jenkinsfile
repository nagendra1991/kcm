pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
               checkout scm
            }
        }
        stage('Clean') {
            steps {
                sh 'mvn clean'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
