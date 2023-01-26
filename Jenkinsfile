pipeline {
    agent { label 'master' }

    stages {
       stage('Checkout') { 
                    steps {
                            git branch: 'main', url: "git@github.com:Nortsx/jenkinsansiblebook.git", credentialsId: 'github_key'
                    }   
       }  
        stage('Install postgresql and create directory') {
                    steps {
                        sh 'ansible-playbook -i hosts playbook.yml'
                        }
                    }
                 
    }
}
