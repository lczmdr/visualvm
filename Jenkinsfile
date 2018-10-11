pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('Checkout') {
      steps {
        junit(allowEmptyResults: true, keepLongStdio: true, testResults: '**/*.xml')
      }
    }
  }
}