pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        retry(3) {
          echo 'Building....'
        }
      }
    }
  }
}
