pipeline {
  agent any
  stages {
    stage('Build') {
      agent any
      steps {
        sh '''cd /var/www/starg8.com/sportid/deploy;
cap starg8 deploy;'''
      }
    }
  }
}