pipeline {
    agent { label '' }
  
    }
    stages {
        stage('Install postgresql and create directory') {
                    steps {
                        sh 'ansible-playbook -i dev-servers site.yml'
                        }
                    }
                 
    }
}
