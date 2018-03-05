pipeline {
  agent {
    docker {
      image 'maven:3-alpine'
      args '-v "%HOMEPATH%/.m2":/root/.m2 -v "%HOMEPATH%":/home'
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