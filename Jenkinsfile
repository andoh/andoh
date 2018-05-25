pipeline {
  agent any
  stages {
    stage('Build') {
      agent any
      steps {
        sh '''whoami;
cd /home/jenkins/sportidfront;
ssh starg8.com;
ls -la;'''
      }
    }
  }
}