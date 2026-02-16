pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo "=============================="
                echo "Branch : HOTFIX/ISSUE-22"
                echo "Task   : Critical Bug Fix"
                echo "Status : Running Pipeline..."
                echo "=============================="
            }
        }

        stage('Build') {
            steps {
                echo "Building Hotfix code..."
            }
        }

        stage('Test') {
            steps {
                echo "Running regression tests for issue-22..."
                echo "Verifying bug fix..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying hotfix to production URGENTLY..."
            }
        }
    }

    post {
        success {
            echo "hotfix/issue-22 pipeline completed!"
        }
    }
}