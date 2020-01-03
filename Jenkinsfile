pipeline {
  agent {
    node {
      label 'qa-build'
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