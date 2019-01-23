pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sleep 2
        catchError() {
          echo 'hello'
          timestamps() {
            echo 'hi'
          }

        }

      }
    }
  }
}