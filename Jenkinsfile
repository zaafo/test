#!groovy
pipeline {
  agent {
    label ""
  }
    stages{  
        stage('lint') {
          steps {
            script {
              sh "find . -name Chart.yaml | xargs -I{} cd \"\$(dirname {})"
              sh "helm ."
            }
          }
        }
    }
}
            
