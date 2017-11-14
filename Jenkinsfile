
//Jenkinsfile (Declarative Pipeline)

pipeline {
    agent any

    stages {
        stage ('checkout') {
          steps{
            checkout scm
          }
        }
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
