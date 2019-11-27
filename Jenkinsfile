pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'echo "Building..."'
          }
        }

        stage('Build 2') {
          steps {
            echo 'Hello'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        sh 'echo ${PWD}'
      }
    }

  }
}