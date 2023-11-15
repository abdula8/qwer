pipeline {
    agent any 
    stages {
    stage('maven install') {
      steps {
        withMaven(globalMavenSettingsConfig: '', jdk: '', maven: 'maven latest', mavenSettingsConfig: '', traceability: true) {
        // some block
        sh 'mvn clean install'
        }
      }
    }
  }
}
