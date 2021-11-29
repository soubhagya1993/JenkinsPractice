pipeline {
    agent any
    environment {
       DISABLE_AUTH = 'soubhagya'
    }
    stages {
        stage('Build') { 
            steps {
                echo "Hello ${env.DISABLE_AUTH}"
            }
        }
        stage('Test') { 
            steps {
                echo "test done"
            }
        }
        stage('Deploy') { 
            steps {
                echo "deploy done" 
            }
        }
    }
}