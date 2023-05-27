pipeline {
    agent any

    stages {

        stage ( 'ssh to ec2 instance') {
            steps {
                sshagent (['manu-ssh']) {
                    sh 'ssh root@172.105.152.100 "docker ps"'
                }
             }
         } 
      }
   }