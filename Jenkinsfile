pipeline {
  agent any
  stages {
    stage('gather_inputs') {
      steps {
        sh 'find $INPUT_FILE'
        sha1 '$INPUT_FILE'
      }
    }
    stage('process') {
      steps {
        sh 'echo $INPUT_FILE'
      }
    }
  }
}