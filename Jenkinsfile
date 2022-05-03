pipeline{
 agent any  
  stages {
    stage('maven install') {
      steps {
        withMaven(globalMavenSettingsConfig: 'null', jdk: 'java', maven: 'Maven3', mavenSettingsConfig: 'null') {
            sh 'mvn clean install'
        }        
      }
    }
  }  
}
