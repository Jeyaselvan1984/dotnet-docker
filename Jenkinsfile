pipeline {
  agent {
    docker {
      image 'maven:3.3.9-jdk-8'
    }

  }
  stages {
    stage('Build') {
      steps {
        dir(path: 'samples/aspnetapp')
        sh 'docker build --pull -t aspnetapp .'
      }
    }

  }
}