pipeline {
  agent {
    docker {
      image 'python:3.5.1'
    }
    
  }
  stages {
    stage('error') {
      steps {
        echo '"test"'
        sh 'touch testing'
      }
    }
  }
}