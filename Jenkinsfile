pipeline {
  agent {
    node {
      label 'jenkins-agent-node'
    }

  }
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'build test'
          }
        }

        stage('test2-build ') {
          steps {
            sh 'echo "Test2-build"'
          }
        }

        stage('uname -r') {
          steps {
            sh 'uname -r '
          }
        }

      }
    }

    stage('Test') {
      steps {
        echo 'Test '
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy'
      }
    }

  }
}