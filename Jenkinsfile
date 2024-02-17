pipeline {
    agent { label 'master' } 
    
    stages {
        stage ('Build Image') { 
            steps { 
                script {
                    dockerapp = docker.build("thiago1souto/api-produto:${env.BUILD_ID}", '--file ./src/Dockerfile ./src') 
                }       
            }
        }

    }



}

