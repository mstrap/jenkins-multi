pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        echo "start ..."
        sh "date"
      }
    }
    stage('Test') {
      steps {
        echo "start ..."
        sh "date"
        sh "exit 0"
      }
    }
    stage('Test 2') {
      steps {
        echo "start ..."
        sh "date"
        sh "exit 0"
      }
    }
  }

  post { 
    always { 
      echo 'I will always say Hello again!'
    }
  }
}
