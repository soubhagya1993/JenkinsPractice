pipeline {
    agent any
    env.MY_NAME = 'SOUBHAGYA' 
    stages {
        stage('Build') { 
            steps {
                echo "Hello $MY_NAME"
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