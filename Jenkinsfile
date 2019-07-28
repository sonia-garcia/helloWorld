pipeline {
  agent any
  stages {
    stage('DEV') {
      steps {
        bat(script: 'npm run build', returnStdout: true)
      }
    }
  }
}