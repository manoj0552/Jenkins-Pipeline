node{
stage('checkout'){
    
    node {
    checkout([
         $class: 'GitSCM',
         branches: scm.branches,         
         extensions: scm.extensions,
         userRemoteConfigs: [ [ credentialsId:'Manoj2', url:'https://github.com/manoj0552/Jenkins-Pipeline.git' ] ]
    ])
 }
 
 stage('package'){
     bat 'gradle build'
     
 }

}

    
}
