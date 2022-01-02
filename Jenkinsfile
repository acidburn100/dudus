
pipeline {
  agent any
  stages {
    stage ("IP") {
      steps {
    //    script {
      //  }
        echo "${env.K8S_VM_IP}"
        bat 'helm ls -A'
        bat 'helm upgrade -i flaskapp C:/Documents/Backedup-24-Dec-21/project/app/helm_chart/flaskapp'
      }
    }

}
}
