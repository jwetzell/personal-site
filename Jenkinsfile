pipeline {
  agent any
  stages {
    stage('error') {
      agent {
        docker {
          image 'klakegg/hugo'
        }

      }
      steps {
        sh 'huge version'
      }
    }

  }
}