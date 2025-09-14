pipeline {
agent any
tools{
maven 'Maven3'
jdk 'Jdk11'
}
stages {
stage('Compile') { 
    steps {
    sh 'mvn compile'
    }
 }
stage('test'){ 
    steps {
    sh 'mvn test'
   }
 }
stage('Package'){ 
    steps {
   sh 'mvn package'
  }
  }
}
}
