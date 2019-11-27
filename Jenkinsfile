pipeline {
  agent any
  stages {
    stage('Send Email') {
      steps {
        emailext(subject: 'Hello from jenkins', body: 'Hello World', from: 'max.pronko@gmail.com', to: 'max.pronko@gmail.com')
      }
    }

  }
}