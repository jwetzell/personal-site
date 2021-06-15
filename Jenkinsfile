pipeline {
  agent {
    docker {
      image 'klakegg/hugo:latest'
    }

  }
  stages {
    stage('') {
      steps {
        sh 'hugo build'
      }
    }

  }
}