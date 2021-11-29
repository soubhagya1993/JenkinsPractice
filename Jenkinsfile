pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                script { 
                env.Username = soubhagya
                }
        echo "The username  is $Username"
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