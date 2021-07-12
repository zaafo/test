#!groovy
pipeline {
  agent {
    label ""
  }
    stages{  
        stage('lint') {
          steps {
            script {
              sh "pwd"
              sh "ls"
              sh "helm lint ."
            }
          }
        }
    }
}
            
