pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Begin....'
        echo 'Building..'
        bat 'mvn clean install'
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
