pipeline {
  agent {
    any {
      
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
            sh 'npm install'
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
