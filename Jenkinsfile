node {
    checkout scm
    def customImage = docker.build("emmamaidana/ubuntu")
    sh "${customImage}"
}