pipeline {
  agent {
    node {
      label 'Node-Ritesh'
    }

  }
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/riteshakadu/Spring-Boot-Sample-Project.git', branch: 'master')
      }
    }

    stage('Build Code') {
      steps {
        sh 'mvn package'
      }
    }

  }
}