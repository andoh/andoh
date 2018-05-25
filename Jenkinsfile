pipeline {
  agent any
  stages {
    stage('Build') {
      agent any
      steps {
        ws(dir: '/home/') {
          sh '''#!/bin/sh
pwd'''
        }

        sh 'pwd'
      }
    }
  }
}