pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'echo "Run Gradle build"'
      }
    }

    stage('error') {
      steps {
        sh 'echo "w"'
      }
    }

  }
}