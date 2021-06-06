pipeline {
    agent any
    
    stages {
        stage('Deploy') {
          steps{
        sh 'ssh -o StrictHostKeyChecking=no root@34.233.125.61 sudo yum install git -y'
        sh 'ssh -o UserKnownHostsFile=/dev/null -o StrictHostKeyChecking=no root@34.233.125.61 sudo git clone git@github.com:yg57404/op.git'  
     }
   }
 }
}
