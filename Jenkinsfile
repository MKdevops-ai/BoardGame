pipeline {
    agent {label 'S1'}
    
    
    tools {
        maven 'M1'
        jdk 'JDK19'
    }

    stages {     
        stage('Compile') {
            steps {
               sh "mvn compile"
            }
        }
        
        stage('Test') {
            steps {
                sh "mvn test"
            }
        }
        
        stage('Build') {
            steps {
                sh "mvn package"
            }
        }
    }
}
