#!groovy
pipeline {
  agent {
    label ""
  }
    stages{  
        stage('lint') {
          steps {
            script {
              commonFunction_OP.lintHelm()
            }
          }
        }
    }
}
            
