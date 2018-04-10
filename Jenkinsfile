pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('Maven Version') {
      steps {
        sh 'mvn -v'
      }
    }
  }
}