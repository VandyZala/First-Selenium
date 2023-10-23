pipeline {
  agent any
  stages {
    stage('Subscribed user') {
      steps {
        bat 'login_subscribed.py'
      }
    }
    stage('Expired user') {
      steps {
        bat 'login_expired_trail.py'
      }
    }
  }
}
