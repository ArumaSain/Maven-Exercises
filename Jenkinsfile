pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Starting Build step'
        sh 'git checkout answer3'
        sh 'mvn clean install -Dlicense.skip=true'
        echo 'finish build step'
      }
    }

  }
}