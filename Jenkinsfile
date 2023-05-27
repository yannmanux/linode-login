pipeline {
    agent any

    stages {

        stage ( 'Deploy') {
            steps {
                sshagent (credentials : ['manu-ssh']) {
                    sh 'ssh root@172.105.152.100 '
                }
             }
         } 
      }
   }