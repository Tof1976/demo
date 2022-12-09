pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Begin....'
        echo 'Building..'
        bat(script: 'mvn clean install', returnStatus: true, returnStdout: true)
        echo 'END...'
      }
    }

    stage('Test') {
      steps {
        echo 'Testing..'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }

  }
}
