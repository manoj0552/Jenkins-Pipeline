node{
stage('checkout'){
    
    checkout([ 
    $class:'GitSCM',
    branches: 'master',
    userRemoteConfigs:[ [ credentialsId:'Manoj2',url:'git@github.com:manoj0552/gradle-simple.git'] ]
       
     ])
}

    
}
