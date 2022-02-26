pipeline{
  agent any
  tools {
    name: 'maven', type: 'maven'
  }
  stages{
      stage('Bulid stage'){
        steps{
          sh 'mvn clean package'
        }
      }
  }
}