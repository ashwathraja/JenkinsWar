node{
    stage('Deploy to Tomcat'){
    sshagent(['tomcat-pipeline-deploy']) {
    sh 'scp -o StrictHostKeyChecking=no target/*.war ec2-user@18.219.83.247:/opt/apache-tomcat-9.0.16/webapps/'
    }
    }
}
