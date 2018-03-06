pipeline {
  agent {
    docker {
      image 'maven:3-alpine'
      args '-v /"C:/Users/nwg/.m2":/"root/.m2"'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        echo 'We made it past start!'
      }
    }
  }
}