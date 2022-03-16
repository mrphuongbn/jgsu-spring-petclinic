pipeline {
  agent any
  stages {
    stage('dev') {
      steps {
        sh '''./mvnw package
java -jar target/*.jar
'''
      }
    }

  }
}