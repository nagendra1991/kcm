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
                bat 'mvn clean'
            }
        }
        stage('Install') {
            steps {
                bat 'mvn install'
            }
        }   
        stage('Package') {
            steps {
                bat 'mvn package'
            }
        }    
    }
}
