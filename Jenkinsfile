pipeline {
  agent {
    docker {
      args '-u root -v /Users/nwg/.m2:/root/.m2 -v "%HOMEPATH%":/home'
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