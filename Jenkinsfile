pipeline {
  agent any
  stages {
    stage('') {
      steps {
        withMaven(jdk: 'JDK8u152', maven: 'Maven_3.5.2') {
          sh 'mvn clean install'
        }
        
      }
    }
  }
}