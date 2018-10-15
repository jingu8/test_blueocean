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
    stage('') {
      steps {
        git(url: 'https://github.com/jingu8/test_blueocean', branch: 'main', credentialsId: 'e0449cadc8da9c0782c01863eac854a642ccf33d')
      }
    }
  }
}