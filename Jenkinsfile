pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                
            }
        }
        stage('Package') {
            steps {
                echo 'Packaging...'
                
                bat 'docker build -t my-java-app .'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                
                bat 'docker push my-java-app'
            }
        }
    }
}
