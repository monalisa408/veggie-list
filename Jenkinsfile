pipeline {
  agent any
  stages {
    stage('Initial build') {
      agent {
        dockerfile {
          filename 'angular/ngcontainer:latest'
        }

      }
      steps {
        sh 'echo \'hello world\''
      }
    }

  }
}