node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'Dockerweb') {

        def customImage = docker.build("bharathyash1/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
