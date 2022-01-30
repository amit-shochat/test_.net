pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'dotnet'
    }

  }
  stages {
    stage('BUILD') {
      steps {
        sh 'dotnet run'
      }
    }

  }
  environment {
    HOME = '/tmp'
  }
}