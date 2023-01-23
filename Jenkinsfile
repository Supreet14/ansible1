pipeline {
    agent any
    stages {
        stage('rmfile') {
            steps {
     ansiblePlaybook credentialsId: '44.211.198.19', disableHostKeyChecking: true, installation: 'ansible', inventory: 'dev.inv', playbook: 'rmdir.yml' 
}
            }
        }
    }
