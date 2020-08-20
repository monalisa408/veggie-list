pipeline {
  agent any
  stages {
    stage('Initial build') {
      agent {
        docker {
          image 'angular/ngcontainer:0.10.0'
        }

      }
      steps {
        sh 'echo \'hello world\''
      }
    }

  }
}