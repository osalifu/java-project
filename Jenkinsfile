pipeline {
  agent any
  
  stages {
    stage ('Build') {
      steps {
        sh '/fmac/prod/tools/ant/ant-1.10.1/bin/ant -f build.xml -v'
      } 
    }
  }
}