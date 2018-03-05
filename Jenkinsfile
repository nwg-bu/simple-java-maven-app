pipeline {
  agent {
    docker {
      image 'maven:3-alpine'
      args "-v 'Users/nwg/.m2':/root/.m2 -v"
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