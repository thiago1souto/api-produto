pipeline {
    agent any 
    
    stages {
        stage ('Build Image') { 
            steps { 
                cript {
                    dockerapp = docker.build("thiago1souto/api-produto:${env.BUILD_ID}", '-f ./src/Dockerfile ./src') 
                }       
            }
        }

    }



}

