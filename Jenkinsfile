pipeline {
  agent any
  stages {
    stage('error') {
      agent {
        docker {
          image 'klakegg/hugo:ci'
        }

      }
      steps {
        sh 'hugo version'
      }
    }

  }
}