Pipeline {
 agent any
    stage('checkout'){
        git url: 'https://github.com/chikoo4422/demo-mavenproject.git'
    }
    stage('build'){
        sh "./mvnw clean install -DskipTests"
    }
     
}