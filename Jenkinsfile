pipeline {
  agent any
  stages {
    stage('Build result') {
      steps {
        sh 'sudo docker-compose up -f'
        sh 'sleep 25'
        sh 'sudo docker-compose down'
      }
    }
  }
}
