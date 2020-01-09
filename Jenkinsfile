pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        dir(path: 'samples/aspnetapp')
        sh 'docker build --pull -t aspnetapp .'
      }
    }

  }
}