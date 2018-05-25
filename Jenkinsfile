pipeline {
  agent any
  stages {
    stage('Build') {
      agent any
      steps {
        sh '''ps;
cd /home/ando/SportID/sportidfront;
cap starg8 deploy;
'''
      }
    }
  }
}