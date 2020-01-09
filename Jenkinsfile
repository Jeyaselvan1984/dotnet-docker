pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''cd samples;
cd aspnetapp;
docker build --pull -t aspnetapp .'''
      }
    }

  }
}