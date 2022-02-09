
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
               sh   'mvn build'
  
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
