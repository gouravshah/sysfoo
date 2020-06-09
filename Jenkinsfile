pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        tool(name: 'Maven 3.6.3', type: 'maven')
        sh '${mvnHome}/bin/mvn compile'
      }
    }

  }
}