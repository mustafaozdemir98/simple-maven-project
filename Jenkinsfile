pipeline {
  agent {
    node {
      label 'windowsage'
    }

  }
  stages {
    stage('Clean') {
      steps {
        bat 'mvn clean'
      }
    }

    stage('Compile') {
      steps {
        bat 'mvn compile'
      }
    }

  }
}