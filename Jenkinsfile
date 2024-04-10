pipeline {
    agent any

    stages {
        stage ('Build Image') {
            steps {
                script {
                    dockerapp = docker.build("rafael9br/api-produto:${env.BUILD_ID}" , '-f ./src/Dockerfile ./src')
                }
            }                
        }
    }
}
