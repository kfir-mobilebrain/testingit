pipeline {
    agent any

    stages {
        stage('Hello - Version 2') {
            steps {
                echo 'Hello World'
            }
        }
        stage('checkout') {
            steps {
                checkout scm
            }
        }
        stage('list files') {
            steps {
                sh 'ls'
            }
        }
    }
}