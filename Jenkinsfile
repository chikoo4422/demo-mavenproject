pipeline {
  agent any
  stages{
    stage('checkout'){
       steps{
        git url: 'https://github.com/chikoo4422/demo-mavenproject.git'
      }
    }
    stage('build'){
       steps{
        sh "./mvnw clean install -DskipTests"
    }
  }
     
}
}
