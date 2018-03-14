pipeline {
  agent any
  stages {
    stage('Step 1') {
      steps {
        echo 'Step 1 executed! ${KOMUNIKAT}'
      }
    }
    stage('Step 2') {
      steps {
        echo 'Step 2 executed!'
      }
    }
    stage('Build_job') {
      steps {
        build 'ssh_test'
      }
    }
  }
}