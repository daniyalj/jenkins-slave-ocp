node(''){
    stage('Deploy App') {
        script{
        openshift.withCluster('stagingcluster') {
            openshift.withProject() {
                
                sh "oc whoami"
                sh "oc projects"
               
 

            }
        }
    }
}
}
