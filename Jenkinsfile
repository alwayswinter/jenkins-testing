pipeline {
  agent {
    docker {
      image 'centos6.9'
    }
    
  }
  stages {
    stage('error') {
      steps {
        echo '"test"'
      }
    }
  }
}