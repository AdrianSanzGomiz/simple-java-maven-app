pipeline {
  agent {
    docker {
      image 'hello-world'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'mvn clean install'
      }
    }

  }
}