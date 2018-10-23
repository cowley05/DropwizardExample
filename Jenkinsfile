pipeline {
  agent any
  stages {
    stage('test input') {
      steps {
        input(message: 'enter version number', id: 'version', ok: 'ok', submitter: 'submitter', submitterParameter: 'submitterparam')
      }
    }
  }
}