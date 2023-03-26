pipeline {
  
  agent {
    label {
      label "built-in"
      customWorkspace "/mnt/ass"
    }
  }
  stages {
    stage ("stage1") {
      steps {
        
        sudo "ansible-playbook /home/ashutosh/test.yaml"
   
  
  
      }
     
    }
  
  }
}
