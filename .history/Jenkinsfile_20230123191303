pipeline {
    agent any
    stages {
        stage('rmfile') {
            steps {
     ansiblePlaybook credentialsId: 'webserver', disableHostKeyChecking: true, installation: 'ansible', inventory: 'dev.inv', playbook: 'rmdir.yml' 
}
            }
        }
    }
