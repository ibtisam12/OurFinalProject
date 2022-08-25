pipeline {
  agent any
  stages {
    stage('Pull code') {
      steps {
        bat(script: 'git pull origin master', returnStatus: true)
      }
    }

  }
}