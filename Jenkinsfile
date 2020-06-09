pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        tool(name: 'Maven 3.6.3', type: 'Maven')
        sh 'mvn compile'
      }
    }

  }
}