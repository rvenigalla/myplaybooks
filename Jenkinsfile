pipeline {
  agent any
 stages {

  stage('Run Playbook') {
    steps {
      ansiblePlaybook installation: 'ansible', inventory: '/home/ec2-user/inventory', playbook: 'myplay1.yml'
    }
  }
 } 
}
