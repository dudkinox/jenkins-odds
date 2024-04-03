// Pipeline script for Jenkins
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                git branch: 'main', url: 'https://github.com/dudkinox/stock-application'
            }
        }
        stage('Discord noti') {
            steps {
                sh 'echo Discord noti'
            }
        }
    }
}
