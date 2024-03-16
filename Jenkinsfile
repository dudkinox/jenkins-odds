pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                git branch: 'main', url: 'https://github.com/dudkinox/jenkins-odds'
            }
        }
        stage('Discord noti') {
            steps {
                sh 'echo Discord noti'
            }
        }
    }
}
