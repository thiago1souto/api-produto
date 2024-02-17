pipeline {
    agent any 
    
    stages {
        stage ('Build Image') { 
            steps { 
                script {
                    dockerapp = docker.build("thiago1souto/api-produto:1.0", '--file ./src/Dockerfile ./src') 
                }       
            }
        }

    }



}

