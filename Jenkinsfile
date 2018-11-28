pipeline {
    agent {
      label 'maven'
    }
  stages {
    stage('Build App') {
      steps {
        sh 'ls'
        script{
        openshift.withCluster() {
            openshift.withProject() {
                sh "oc whoami"
                sh "oc projects"
                
                  }
                }
             }
          }
         }
      }
    }
