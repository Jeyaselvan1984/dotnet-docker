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
      }
    }

    stage('Run') {
      steps {
        sh 'docker run --name aspnetcore_sample --rm -it -p 5000:80 aspnetapp'
      }
    }

  }
}