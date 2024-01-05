pipeline {
    agent any

    stages {
        stage('Build Image'){
            steps {
                script {

                  dockerapp = docker.build("updateinformatica/api-produto", '-f ./src/Dockerfile ./src')
                 
                }
                
          }
        }
    }
}