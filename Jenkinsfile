pipeline {
  agent any
  stages {
    stage('Prepare the Build Environment') {
      steps {
        parallel(
          "Prepare the Build Environment": {
            echo 'Preparing the build environment'
            
          },
          "Prepare DEV": {
            powershell(script: 'ExtractBuild.ps1', encoding: 'UTF-8', returnStatus: true, returnStdout: true)
            
          }
        )
      }
    }
  }
  environment {
    ORG = 'VA'
  }
}