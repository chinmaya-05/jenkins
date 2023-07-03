pipeline {
    agent any
    environment{
        ENV_URL= "pipeline.google.com" // pipeline variables
        SSHCRED= credentials('SSH_CRED')
    }
    stages{
        stage('stage one'){
            environment{
                ENV_URL= "stage.google.com" // pipeline variables
            }
            steps {
                echo "This is stage one"
                echo "Name of the URL is ${ENV_URL}"
            }
            
        }
        stage('stage Two'){
            steps {
                echo "This is stage Two"
            }
            
        }
        stage('stage Three'){
            steps {
                echo "This is stage Three"
                echo "Name of the URL is ${ENV_URL}"
            }
            
        }
    }

}