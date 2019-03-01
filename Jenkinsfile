pipeline{
 agent any
 tools {
      maven 'maven3.6.0'
      jdk 'jdk1.8.0'
  }
  
  stages {
     stage('Build') {
     steps {
     
        sh "mvn -B -DskipTests clean package"
       
       }
      }   
 }
}
