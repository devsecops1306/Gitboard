pipeline {
    agent any

    tools {
        jdk 'JDK_17'
        maven 'Maven3'
    }
    
    stages {
        stage('Compile') {
            steps {
                sh 'mvn compile'
            }
        }
    
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
    
  
        stage('Build') {
            steps {
                sh 'mvn package'
            }
        }
}
}
