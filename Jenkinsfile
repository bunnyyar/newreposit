pipeline {
    agent any

     tools {
        
        maven 'Maven 3.2.1'  
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