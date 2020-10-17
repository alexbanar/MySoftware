pipeline {
  agent any
  stages {
    stage('print') {
      steps {
        git 'https://github.com/alexbanar/MySoftware.git'
      }
    }
    stage('print2') {
      steps {
        bat 'python welcome.py'
      }
    }
  }
}
