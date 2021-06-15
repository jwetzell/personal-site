pipeline {
  agent any
  stages {
    stage('Hugo Build') {
      agent {
        docker {
          image 'klakegg/hugo:ci'
        }

      }
      steps {
        sh 'hugo build --minify --buildDrafts'
      }
    }

  }
}