pipeline {
    agent any

    stages {

        stage ( 'Deploy') {
            steps {
                sshagent (credentials : ['manu-ssh']) {
                    sh '''
                        ssh -o StrictHostKeyChecking=no -p 22 root@172.105.152.100 "docker ps"
                    '''
                }
             }
         } 
      }
   }