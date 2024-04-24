pipeline {
    agent any
    stages {
        stage('Docker Build') {
            steps {
                script {
                    docker.build('my-test')
                }
            }
        }
    }
}
