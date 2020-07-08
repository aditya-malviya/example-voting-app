pipeline {
  agent any
  stages {
    stage('Build result') {
      steps {
        sh 'sudo docker-compose up -d'
        sh 'sleep 25'
        sh 'sudo docker-compose down'
      }
    }
  }
}
