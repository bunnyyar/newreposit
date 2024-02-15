pipeline {
    agent any

    tools {
        maven:'maven'
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