pipeline {
    agent any
    stages {
        stage('Build') {
            git branch: 'master',
                url: 'https://github.com/Newmi1988/httpserv'

                def customImage = docker.build("go-http-server")
        }
    }
}