pipeline {
  agent {
        docker {
            image 'node:6-alpine'
            args '-p 3000:3000'
        }
    }
     environment {
            HOME = '/tmp'
        }

  }
  stages {
    stage('') {
      steps {
        sh 'dotnet run '
      }
    }

  }
}
