pipeline{
  agent any
  tools {
    maven 'maven3'
  }
  stages{
    stage('Bulid stage'){
      steps{
        sh 'mvn clean package'
      }
    }
  }
}