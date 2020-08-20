pipeline {
  agent any
  stages {
    stage('Initial build') {
      agent {
        docker {
          image 'angular/ngcontainer:latest'
        }

      }
      steps {
        sh 'echo \'hello world\''
      }
    }

  }
}