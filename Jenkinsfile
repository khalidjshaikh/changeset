pipeline {
    agent any 
    stages {
        stage(‘Build’) { 
            steps {
                sh ""
            }
        }
        stage(‘Test’) { 
            steps {
                sh ""
            }
        }
        stage(‘Deploy’) { 
            steps {
                parallel(
                  a: {
                    sh ""
                  },
                  b: {
                    sh ""
                  }
                )
            }
        }
    }
}