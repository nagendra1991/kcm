pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('clean') {
            steps {
                sh maven clean
            }
        }
    }
}
