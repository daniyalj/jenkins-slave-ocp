node(''){
    stage('Deploy App') {
        script{
        openshift.withCluster('stagingcluster') {
            openshift.withProject() {
                sh "oc login https://loadbalancer.cce8.example.opentlc.com --token=$(oc whoami -t) --insecure-skip-tls-verify=true"
                sh "oc whoami"
                sh "oc projects"
               
 

            }
        }
    }
}
}
