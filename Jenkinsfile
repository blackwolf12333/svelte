pipeline {
  agent {
    docker {
      image 'node'
    }

  }
  stages {
    stage('install') {
      steps {
        sh 'npm install'
        sh 'npm run build'
      }
    }

  }
}