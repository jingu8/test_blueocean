pipeline {
  agent any
  stages {
    stage('Get Github Code') {
      steps {
        git(url: 'https://github.com/jingu8/gradledemo', branch: 'main')
      }
    }
  }
}