pipeline {
  agent {
    docker {
      args '-v "%HOMEPATH%\.m2":\root\.m2 -v "%HOMEPATH%":\home'
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