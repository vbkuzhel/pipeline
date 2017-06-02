pipeline {
  agent any
  stages {
    stage('Init') {
      steps {
        echo 'hello'
        isUnix()
      }
    }
    stage('perform') {
      steps {
        parallel(
          "paralel step 1": {
            echo 'paaralel job 1'
            
          },
          "paralel step 2": {
            echo 'paaralel job 2'
            
          },
          "stage stage": {
            echo 'ssss'
            
          }
        )
      }
    }
    stage('stage 3') {
      steps {
        echo 'ooooo'
      }
    }
  }
}