pipeline {
  agent any
  stages {
    stage('Build'){
      steps {
        sh 'mvn install'
      }
    }
    stage('Test'){
      steps {
        sh 'mvn test'
      }
    }
  }
}
