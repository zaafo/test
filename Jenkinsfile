#!groovy
pipeline {
  agent {
    label ""
  }
    stages{  
        stage('lint') {
          steps {
            script {
              sh "find . -name Chart.yaml | xargs -I{} /bin/sh -c 'cd \"\$(dirname {})\"; helm lint .'"
            }
          }
        }
    }
}
            
