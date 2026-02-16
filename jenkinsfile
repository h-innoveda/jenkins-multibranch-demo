pipeline {
    agent any 
    
    stages {
        stage('Hello'){
           steps {
                echo "=============================="
                echo "Branch : MAIN"
                echo "Task   : Production Deployment"
                echo "Status : Running Pipeline..."
                echo "=============================="
        }
    }
    stage('Build'){
        steps{
            echo "Building the main branch"
        }
    }
    stage('Test'){
        steps{
            echo "Testing On main branch"
        }
    }
    stage('Deploy'){
        steps{
            echo "Deployment of Main branch"
        }
    }
    post{
    success {
        echo "Main branch successfully executed"
    }
    }   
}