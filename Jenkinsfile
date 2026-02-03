pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/sakshishah1710/end-to-end-devops-aws-ci-cd.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Build stage completed'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage completed'
            }
        }
    } 
}
