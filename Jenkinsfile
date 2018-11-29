node(''){
    stage('Deploy App') {
        script{
        openshift.withCluster('staging-cluster') {
            openshift.withProject() {
                
                sh "oc whoami"
                sh "oc projects"
               
 

            }
        }
    }
}
}
