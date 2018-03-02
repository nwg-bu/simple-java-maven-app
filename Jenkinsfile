pipeline {
  agent {
    docker {
      args "-v '/Users/nwg/.m2:/root/.m2'"
      image 'maven:3-alpine'
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