#!groovy

pipeline {
  agent {
    label "jenkins-nodejs"
  }
// Lint de la chart
    stage('lint Yaml config files') {
        steps {
            script {
                commonFunction_OP.lintHelm()
            }
        }
    }
}



