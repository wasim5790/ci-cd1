pipeline {
  agent any
    
  stages {
        stage('Deploy') {
          steps{
        sh 'sudo yum install httpd -y'  
        sh 'cd /var/www/html; sudo git clone git@github.com:wasim5790/demo-project.git'
     }
   }
 }
}
