node{
  stage("checkout"){
  checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: []])

  }
  stage("Hello-World"){
    sh 'echo"heloo"'
  }
}
