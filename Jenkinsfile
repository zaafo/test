#!groovy
pipeline {
  agent {
    label ""
  }
    stages{  
        stage('lint') {
          steps {
            script {
              commonFunction.helmInit()
            }
          }
        }
    }
}
            
