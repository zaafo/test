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
              sh "/usr/local/bin/helm lint ."
              sh "/usr/local/bin/helm package ."
            }
          }
        }
    }
}
