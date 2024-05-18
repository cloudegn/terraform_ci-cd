pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                // Add your build commands here
                sh 'echo "Buildin the project..."'
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
    
    post {
        success {
            // This block will be executed if the pipeline is successful
            echo 'Pipeline executed successfully!'
        }
        failure {
            // This block will be executed if the pipeline fails
            echo 'Pipeline execution failed!'
        }
    }
}
