pipeline {
  agent any
 stages {

  stage('Run Playbook') {
    steps {
      ansiblePlaybook installation: 'ansible', inventory: '/home/ec2-user/inventory.ini', playbook: 'myplay1.yml'
    }
  }
 } 
}
