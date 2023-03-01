pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'application is build'
            }
        }
         stage('testing') {
            steps {
                echo 'application is testing'
            }
        }
         stage('uat') {
            steps {
                echo 'waiting for user acceptancy'
            }
        }
          stage('release') {
            steps {
                echo 'application is ready to release to production'
            }
        }
        
    }
}
