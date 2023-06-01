pipeline
{
  agent any
 

   stages {
  
    stage( 'Ansible Playbook'){
      steps {
        //Run the Ansible playbook

        sh 'ansible-playbook -i inventory.ini playbook.yml
    }
  }
 }
}

