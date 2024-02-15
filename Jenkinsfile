pipeline {
    agent any

     tools {
        
        maven 'maven 3.9.6'  
    }
    
    stages {
        stage('build') {
            steps {
                sh 'mvn clean install'
            }
        }
        stage('test') {
            steps {
                sh 'echo'
            }
        }
        stage('deploy') {
            steps {
                sh 'echo'
            }
        }
    }

}