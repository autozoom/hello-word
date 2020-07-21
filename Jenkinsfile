pipeline {
  agent any
  stages {
    stage('s1') {
      steps {
        echo 'ciao'
      }
    }

    stage('d1') {
      steps {
        script {
          app = docker.build("getintodevops/example-app")
        }

      }
    }

  }
}