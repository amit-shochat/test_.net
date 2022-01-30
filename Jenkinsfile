pipeline {
  agent {
    docker {
      image 'dotnet'
      args '-p 3000:3000'
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
