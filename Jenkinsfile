pipeline {
  agent {
    node {
      label 'init'
    }

  }
  stages {
    stage('Selecting cloud provider') {
      steps {
        echo 'Select cloud provider'
      }
    }

  }
  environment {
    Azure = 'Azure'
    AWS = 'AWS'
    Gcp = 'Gcp'
  }
}