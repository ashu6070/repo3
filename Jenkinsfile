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
       sh "cp -r /mnt/ass/index.html /home/ashutosh/"
       sh "ansible-playbook /home/ashutosh/test.yaml"
   
  
  
      }
     
    }
  
  }
}
