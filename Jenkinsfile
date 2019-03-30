pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        buildPlugin()
      }
    }
  }
  environment {
    nocheck = '-Dcheckstyle.skip'
  }
}