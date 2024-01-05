pipeline {
    agent any

    stages {
        stage('Build Image'){
            steps {
                script {

                   pipeline {
    agent any

    stages {
        stage('Build Image'){
            steps {
                script {

                  withDockerRegistry(credentialsId: 'docker', toolName: 'docker'){
                    sh "docker build  -t updateinformatica/api-produto ."
                    sh "docker tag prd updateinformatica/api-produto "
                    sh  "docker push updateinformatica/api-produto"
                  }
                }
                
          }
        }
    }
}
                }
                
          }
        }
    }
}