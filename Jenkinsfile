pipeline {
  agent none
  stages {
    stage('Update CRM Solution from SCM') {
      steps {
        node(label: 'Solution') {
          writeFile(file: 'test-pipeline-file', text: 'This is the text')
        }
        
      }
    }
  }
  environment {
    ORG = 'VA'
  }
}