pipeline {
  agent any
  stages {
    stage('Build') {
      agent any
      steps {
        ws(dir: '/home/ando/SportID/sportidback') {
          sh '''#!/bin/bash -el;
cap starg8 deploy'''
        }

      }
    }
  }
}