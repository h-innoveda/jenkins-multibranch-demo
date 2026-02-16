pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo "=============================="
                echo "Branch : FEATURE/PAYMENT"
                echo "Task   : Payment Feature Test"
                echo "Status : Running Pipeline..."
                echo "=============================="
            }
        }

        stage('Build') {
            steps {
                echo "Building Payment Feature code..."
            }
        }

        stage('Test') {
            steps {
                echo "Running Payment gateway tests..."
                echo "Testing transaction flow..."
                echo "Testing refund logic..."
            }
        }
    }

    post {
        success {
            echo "feature/payment pipeline completed!"
        }
    }
}