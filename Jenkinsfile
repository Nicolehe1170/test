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
        sh '''pwd
ls -al
cat Jenkinsfile
exit 0

'''
      }
    }
  }
}