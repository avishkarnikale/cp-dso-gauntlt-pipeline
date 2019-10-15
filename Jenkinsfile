pipeline {
  agent any 
  stages {
    stage('Check XSS ataack'){
      steps {build 'Gauntlt-XSS-Attack'}
    }
    stage('Check SQLi attack'){
      steps {build 'Gauntlt-SQLi-Attack'}
    }
    stage('Check ports'){
      steps {build 'Gauntlt-NMAP-Attack'}
    }
    stage('Check fuzz attack'){
      steps {build 'Gauntlt-FUZZ-Attack'}
    }
  }
}
