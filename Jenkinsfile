pipeline {
    agent { label 'Worker_1' }
    
    stages {
        stage('Build') {
            steps {
                // Add your build commands here
                sh 'echo "Building the project..."'
            }
        }
        
        stage('Test') {
            steps {
                // Add your test commands here
                sh 'echo "Running tests..."'
            }
        }
        
        stage('Deploy') {
            steps {
                // Add your deployment commands here
                sh 'echo "Deploying the project..."'
            }
        }
    }
