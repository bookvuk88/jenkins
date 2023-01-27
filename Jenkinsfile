pipeline {
    agent { label 'master' }

    stages {
        stage('Install postgresql and create directory') {
                    steps {
                        ansiblePlaybook installation: 'Ansible', inventory: 'hosts', playbook: 'playbook.yml'
                        }
                    }
                 
    }
}
