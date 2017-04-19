pipeline {
  agent any
  stages {
    stage('Extract CRM Solution') {
      steps {
        svn 'http://svn.libertyitsazure.com/svn/BTSSS/CRM/trunk/Solutions'
      }
    }
  }
}