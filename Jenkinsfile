pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        parallel(
          "build": {
            echo 'Hi'
            
          },
          "": {
            sh 'pwd'
            
          }
        )
      }
    }
  }
}