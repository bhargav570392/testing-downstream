node 
{

stage('test')
{
build 'Testingupdp'
  
   checkout([$class: 'GitSCM', branches: [[name: '*/test1']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/bhargav570392/testing-downstream.git']]])
}
  
  
}
