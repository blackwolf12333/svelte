pipeline {
  agent any
  stages {
    stage('install') {
      steps {
        sh 'npm install'
        sh 'npm run build'
      }
    }

  }
}