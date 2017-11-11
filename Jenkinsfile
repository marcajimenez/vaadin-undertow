pipeline {
  agent none
  stages {
    stage('error') {
      steps {
        withMaven(jdk: 'JDK8u152', maven: 'Maven_3.5.2') {
          sh 'mvn clean install'
        }
        
      }
    }
  }
}