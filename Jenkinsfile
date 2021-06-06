pipeline {
    agent any
    
    stages {
        stage('Deploy') {
          steps{
        sh 'ssh -o StrictHostKeyChecking=no root@18.234.127.115 sudo yum install httpd -y'
        sh 'ssh -o UserKnownHostsFile=/dev/null -o StrictHostKeyChecking=no root@18.234.127.115 cd /var/www/html/ &&sudo git clone git@github.com:yg57404/op.git'  
     }
   }
 }
}
