node {
    environment {
    ARTIFACT_ID = "emmamaidana/ubuntu:${env.BUILD_NUMBER}"
    }

    stages {
    stage('Build') {
      steps {
        script {
          dir("ubuntu") {
            dockerImage = docker.build "${env.ARTIFACT_ID}"
          }
        }
      }
    }
}