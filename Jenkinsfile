pipeline {
  agent any
  stages {
    stage('Initial') {
      steps {
        echo 'Hello'
      }
    }
    stage('Build') {
      steps {
        sh '''ls -al
cat *
'''
      }
    }
  }
}