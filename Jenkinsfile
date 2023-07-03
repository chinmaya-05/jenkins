pipeline {
    agent any
    environment{
        ENV_URL= "pipeline.google.com"
    }
    stages{
        stage('stage one'){
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
            }
            
        }
    }

}