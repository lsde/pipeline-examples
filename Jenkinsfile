pipeline {
  agent any
  stages {
    stage('gather_inputs') {
      steps {
        sh 'find $INPUT_FILE'
      }
    }
  }
}