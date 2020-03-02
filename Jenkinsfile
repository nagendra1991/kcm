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
        stage('Install') {
            steps {
                sh 'mvn install'
            }
        }   
        stage('Package') {
            steps {
                sh 'mvn package'
            }
        }    
    }
}
