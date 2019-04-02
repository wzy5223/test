node{
  stage('test'){
    dir('/home/wzy/src/BOCC'){
      pomData=readMavenPom file: 'pom.xml'
      version=pomData.getVersion()
      echo version
    }
  }	
}
