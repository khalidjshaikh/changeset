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
      parallel {
        stage('dev'){steps{sh ''}}
        stage('stg'){steps{sh ''}}
        stage('prd'){steps{sh ''}}
      }
    }
  }
}