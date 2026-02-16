pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo "=============================="
                echo "Branch : DEV"
                echo "Task   : Staging Deployment"
                echo "Status : Running Pipeline..."
                echo "=============================="
            }
        }

        stage('Build') {
            steps {
                echo "Building DEV branch code..."
            }
        }

        stage('Test') {
            steps {
                echo "Running tests on DEV branch..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying to STAGING environment..."
            }
        }
    }

    post {
        success {
            echo "DEV pipeline completed successfully!"
        }
    }
}