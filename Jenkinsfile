pipeline {
    agent any
    environment {
       DISABLE_AUTH = 'soubhagya'
    }

    parameters {
        choice(name: 'branch', choices: ['main','dev'])
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