pipeline {
  agent any
  stages {
    stage('Build') {
      agent any
      steps {
        sh '''cd /home/ando/SportID/sportidback;
cap starg8 deploy;
'''
      }
    }
  }
}