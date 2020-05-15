pipeline {
  agent {
    node {
      label 'Windows'
    }

  }
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/Ragavendira1/ExpleoDemo.git', branch: 'master')
      }
    }

    stage('AUT') {
      steps {
        echo 'Selenium Test Cases '
      }
    }

  }
}