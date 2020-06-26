node {
    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerhub-marty') {

        def customImage = docker.build("masservices/docker")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
