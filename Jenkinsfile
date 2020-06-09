pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        tool(name: 'maven', type: 'Maven 3.6.3')
        sh 'mvn compile'
      }
    }

  }
}