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
                
                sh 'docker build -t my-java-app .'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                
                sh 'docker push my-java-app'
            }
        }
    }
}
