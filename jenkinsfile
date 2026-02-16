pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo "=============================="
                echo "Branch : FEATURE/LOGIN"
                echo "Task   : Feature Testing Only"
                echo "Status : Running Pipeline..."
                echo "=============================="
            }
        }

        stage('Build') {
            steps {
                echo "Building Login Feature code..."
            }
        }

        stage('Test') {
            steps {
                echo "Running Login Feature unit tests..."
                echo "Testing login form validation..."
                echo "Testing authentication flow..."
            }
        }
    }

    post {
        success {
            echo "feature/login pipeline completed!"
        }
    }
}