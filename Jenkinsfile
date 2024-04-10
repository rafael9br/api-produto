pipeline {
    agent any

    stages {
        stage ('Build Image') {
            steps {
                script {
                    dockerapp = docker.build("rafael9br/api-produto" , '-f ./src/Dockerfile ./src')
                }
            }                
        }
    }
}
