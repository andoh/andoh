pipeline {
  agent any
  stages {
    stage('Build') {
      agent any
      steps {
        sh '''cd /home/ando/SportID/sportid; cap starg8 deploy
'''
        ws(dir: '/home/ando/SportID/sportidback') {
          sh '''#!/bin/bash -el

cap starg8 deploy'''
        }

      }
    }
  }
}