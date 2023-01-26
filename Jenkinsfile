pipeline {
    gent { label 'master' }
  
    }
    stages {
        stage('Install postgresql and create directory') {
                    steps {
                        sh 'ansible-playbook -i hosts playbook.yml'
                        }
                    }
                 
    }
}
