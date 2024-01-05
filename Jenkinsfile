pipeline {
    agent any

    stages {
        stage('Build Image'){
            steps {
                script {

                    dockerapp = docker.build("updateinformatica/api-produto:2.0", '-f ./src/Dockerfile ./src')
                }
                
          }
        }
    }
}