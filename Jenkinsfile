pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/praveenbe027/ptetestdemo.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Build stage running.....'
            }
        }
        stage('Test') {
            steps {
                echo 'Test stage running.....'
            }
        }
    }
}
