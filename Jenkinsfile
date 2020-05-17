@Library('jenkins-pipeline-shared-lib-sample')_
tage('Print Build Info') {
    printBuildinfo {
        name = "Sample Name"
    }
} stage('Disable balancer') {
    disableBalancerUtils()
} stage('Deploy') {
    deploy()
} stage('Enable balancer') {
    enableBalancerUtils()
} stage('Check Status') {
    checkStatus()
}
