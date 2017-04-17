pipeline {
  agent {
    docker {
      image 'maven:3.5-alpine'
    }
    
  }
  stages {
    stage('Welcome') {
      steps {
        echo 'Hola mundo Jenkins'
      }
    }
    stage('Unit tests') {
      steps {
        sh 'mvn test'
      }
    }
  }
}