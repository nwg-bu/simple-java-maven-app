pipeline {
  agent {
    if (isUnix()) {
        echo "is Unix"
      } else {
        echo "not Unix"
      }
    docker {
      image 'maven:3-alpine'
      args '-v //.m2:/root/.m2'
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