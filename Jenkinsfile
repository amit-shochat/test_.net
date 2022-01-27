pipeline {
  agent {
    node {
      label 'jenkins-agent-node'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }

  }
  environment {
    CI = 'true'
  }
}