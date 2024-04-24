pipeline {
    agent any
    stages {
        stage('Docker Build') {
            steps {
                script {
                    docker build -t my-test .
                }
            }
    }
    }
}
