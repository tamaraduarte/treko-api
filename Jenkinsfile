pipeline{
  agent{
    docker {
      image "node:8-alpine"
    }
  }
  stages {
    stange ("Build"){
      steps {
        sh "npm install"
      }
    }
  }
}
