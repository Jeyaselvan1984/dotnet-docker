pipeline {
  agent {
    node {
      label '1'
    }

  }
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