node{
stage('checkout'){
    
    checkout([ 
    $class:'GitSCM',
    branches:scm.branches,
    extentions:scm.extentions + [ [ $class:'LocalBranch' ] ],
    userRemoteConfigs:[ [ credentialsId:'Manoj2', url:'https://github.com/manoj0552/Jenkins-Pipeline.git' ] ],
    doGenerateSubmoduleConfigurations: false
     ])
}

    
}
