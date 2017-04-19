pipeline {
  agent any
  stages {
    stage('Extract CRM Solution') {
      steps {
        svn(url: 'http://svn.libertyitsazure.com/svn/BTSSS/CRM/trunk/Solutions', changelog: true)
      }
    }
  }
}