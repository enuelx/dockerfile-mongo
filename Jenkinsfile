node('') {
    env.ARTIFACT_ID = "emmamaidana:ubuntu/latest"
    echo "${env.ARTIFACT_ID}"
    docker.withRegistry("", "DockerHubCredentials") {
        checkout scm
        docker.image('my-custom-image').inside {
            sh 'make test'
        }
        // stage('Build') {
        //     dockerImage = docker.build("${env.ARTIFACT_ID}")
        // }
            
    }
}