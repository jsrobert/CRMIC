pipeline {
  agent none
  stages {
    stage('Update SCM') {
      steps {
        svn(url: 'http://svn.libertyitsazure.com/svn/BTSSS/CRM/trunk/Solutions', changelog: true, poll: true)
      }
    }
  }
  environment {
    ORG = 'VA'
  }
}