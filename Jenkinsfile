pipeline {
  agent any
}

stages {
  stage(docker build) {
      steps{
        docker build -t my-testjenkins:v1 . 
      }
  }
}
