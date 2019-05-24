pipeline {
  agent any
  stages {
    stage('QA') {
      environment {
        MyEnv = 'asdf'
      }
      steps {
        sh 'write-output \'testing account\''
        archiveArtifacts '*'
      }
    }
  }
}