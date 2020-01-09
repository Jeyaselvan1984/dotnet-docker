pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''sudo su root;
cd samples;
cd aspnetapp;
/var/lib/docker build --pull -t aspnetapp .'''
      }
    }

  }
}