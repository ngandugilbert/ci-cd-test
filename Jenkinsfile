pipeline{
    agent any
    stages{
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'echo "Building the project..."'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                sh 'echo "Running tests..."'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                sh 'echo "Deploying the application..."'
            }
        }
    }
}