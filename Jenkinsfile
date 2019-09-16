def workspace
node
{
    stage('checkout')
    
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/vetritamil2425/cheatsheet.git']]])
        workspace =pwd()
        
    }
    
    stage('SCA')
    { 
        echo "SCA"
    }
    stage('Build')
    {
        echo "build the code"
        
    }
    stage('testing phase')
    {
        echo 'hello everyone we gonna test'
    }
    }
