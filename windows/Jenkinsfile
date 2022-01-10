
pipeline {
  agent any
  stages {
    stage ("IP") {
      steps {
    //    script {
      //  }
        echo "${env.K8S_VM_IP}"
        bat 'helm ls -A'
        bat 'helm upgrade -i flaskapp C:/Documents/Task/flaskapp'
        //bat 'sh -x -c "kubectl get pods"'
      }
    }

}
}
