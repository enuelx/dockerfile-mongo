node('') {
    env.ARTIFACT_ID = "emmamaidana:ubuntu/latest"
    echo "${env.ARTIFACT_ID}"
    docker.withRegistry("", "DockerHubCredentials") {
        sh 'OK'            
    }
}