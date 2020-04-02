node {
    env.ARTIFACT_ID = "emmamaidana/ubuntu:${env.BUILD_NUMBER}"

    stage('Build') {
        dockerImage = docker.build "${env.ARTIFACT_ID}"
        echo "${dockerImage}"
    }
}