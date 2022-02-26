pipeline{
  agent any
  tools name: 'maven3', type: 'maven'
  stages{
      stage('Bulid stage'){
        steps{
          sh 'mvn clean package'
        }
      }
  }
}