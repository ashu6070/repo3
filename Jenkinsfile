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
        
       sh "ansible-playbook /home/ashutosh/test.yaml"
   
  
  
      }
     
    }
  
  }
}
