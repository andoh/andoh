pipeline {
  agent any
  stages {
    stage('Build') {
      agent any
      steps {
        ws(dir: '/home/ando/SportID/sportidback') {
          sh 'cap starg8 deploy'
        }

      }
    }
  }
}