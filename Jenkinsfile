pipeline {
  agent {
    label "jenkins-nodejs"
  }
    stage{  
        stage('lint') {
          steps {
            sh "#!/bin/sh\nct lint --chart-dirs . --validate-maintainers=false --debug"
          }
        }
    }
}
      
  
