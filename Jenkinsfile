pipeline {
  agent any
  stages {
    stage('Build') {
      agent any
      steps {
        sh '''whoami;
cd /home/jenkins/sportidfront;
cap starg8 deploy --trace;
'''
      }
    }
  }
}