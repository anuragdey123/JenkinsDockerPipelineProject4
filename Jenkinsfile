pipeline {
  agent any

  stages {
    stage('Build Docker Image') {
      steps {
        script {
          sh 'docker build -t localhost:5000/myapp:latest ./app'
        }
      }
    }

    stage('Push to Local Registry') {
      steps {
        script {
          sh 'docker push localhost:5000/myapp:latest'
        }
      }
    }
  }
}
