pipeline {
  agent any
  stages {
    stage('Init') {
      steps {
        echo 'hello'
        isUnix()
      }
    }
    stage('') {
      steps {
        parallel(
          "paralel stage 2": {
            echo 'paaralel job 1'
            
          },
          "paralel stage 1": {
            echo 'paaralel job 1'
            
          }
        )
      }
    }
  }
}