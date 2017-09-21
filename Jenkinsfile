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
        parallel(
          "Build": {
            sh '''pwd
ls -al
cat Jenkinsfile
exit 0

'''
            
          },
          "Bootstrap": {
            build 'Github-at91bootstrap'
            
          }
        )
      }
    }
  }
}