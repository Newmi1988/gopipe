pipeline {
    agent any
    stages {
        stage('Clone') {
            steps{
                git branch: 'master',
                    url: 'https://github.com/Newmi1988/httpserv'
            }
        }
        stage('Build') {
            steps{
                docker.build("go-http-server")
            }
        }
    }
}