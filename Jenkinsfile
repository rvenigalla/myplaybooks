pipeline {
  agent any
 stages {

  stage('Run Playbook') {
    steps {
      sh '/bin/ansible-playbook -i /home/ec2-user/inventory.ini myplay1.yml'
      
    }
  }
 } 
}
