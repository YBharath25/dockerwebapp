node {

    checkout scm

    docker.withRegistry('https://hub.docker.com/', 'bharathyash1') {

        def customImage = docker.build("bharathyash1/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
