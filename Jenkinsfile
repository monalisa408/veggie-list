pipeline {
  agent any
  stages {
    stage('Initial build') {
      agent {
        docker {
          image 'angular/ngcontainer'
        }

      }
      steps {
        sh 'echo \'hello world\''
      }
    }

  }
}