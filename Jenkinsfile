pipeline {
  agent any
  stages {
    stage ("IP") {
      steps {
    //    script {
      //  }
        //echo "Username: ${env.USERNAME}"
        echo "${env.K8S_VM_IP}"
        ping "${env.K8S_VM_IP}"
        //echo "Password: ${env.PASSWORD}"
      }
    }
  }
}
