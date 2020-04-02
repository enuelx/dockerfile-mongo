node {
    env.ARTIFACT_ID = "emmamaidana/ubuntu:latest"

    stage('Build') {
        dockerImage = docker.build("${env.ARTIFACT_ID}")
        echo "${dockerImage}"
    }
}