pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo "=============================="
                echo "Branch : MAIN"
                echo "Task   : Production Deployment"
                echo "Status : Running Pipeline..."
                echo "=============================="
            }
        }

        stage('Build') {
            steps {
                echo "Building MAIN branch code..."
            }
        }

        stage('Test') {
            steps {
                echo "Running tests on MAIN branch..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying to PRODUCTION environment..."
            }
        }
    }

    post {
        success {
            echo "MAIN pipeline completed successfully!"
        }
    }
}