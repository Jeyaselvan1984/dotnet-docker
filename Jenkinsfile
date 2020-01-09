pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''cd samples;
cd aspnetapp;
sudo docker build --pull -t aspnetapp .'''
      }
    }

  }
}