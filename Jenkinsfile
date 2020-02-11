node{
    
    stage('checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '3fff6072-5793-4db5-9842-f9cea644f606', url: 'https://github.com/jenkins-training/time-tracker.git']]])
    }
    
    stage('static code analysis')
    {
        
        echo "Static code analysis stage"
    }
    stage('unit testing')
    {
        echo "Unit Testing stage"
    }
}
