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
                    sh "docker build --build -t updateinformatica/api-produto:1.0 ."
                    sh "docker tag prd updateinformatica/api-produto:1.0 "
                    sh  "docker push updateinformatica/api-produto:1.0 "
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