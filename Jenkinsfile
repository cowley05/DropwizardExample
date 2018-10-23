pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        waitUntil() {
          fileExists '/dev/null'
        }

      }
    }
  }
}