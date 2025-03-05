pipeline {
    agent {label 'S1'}
    
    tools {
        maven 'maven3999'
       
    }

    stages {     
        stage('Compile') {
            steps {
               sh "mvn compile"
            }
        }
        
    stage('Build') {
            steps {
                sh "mvn clean"
            }
        }
    }
}
