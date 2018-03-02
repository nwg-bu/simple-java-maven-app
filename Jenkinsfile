pipeline {
  agent {
    docker {
      args '-v /Users/nwg/.m2:/root/.m2'
      image 'maven:3.5.2-jdk-8'
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