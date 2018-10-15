pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'This is for demo purpose'
      }
    }
    stage('Test') {
      steps {
        sh 'echo $ENV'
      }
    }
    stage('Timestamp') {
      steps {
        timestamps()
      }
    }
  }
}