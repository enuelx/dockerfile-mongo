pipeline {
    agent {
        docker.withRegistry("", "DockerHubCredentials") {
            docker { image 'node:7-alpine' }
        }
    }
    stage('Test') {
        steps {
            sh 'node --version'
        }
    }
}