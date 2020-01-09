pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''cd samples;
cd aspnetapp;
/var/lib/docker build --pull -t aspnetapp .'''
      }
    }

  }
}