
	 
	 pipeline {
	 agent none
 	    stages {
    	     stage('checkout') {
    	     steps {
    	     checkout([
            $class: 'GitSCM',
            branches: 'master',
            extensions: scm.extensions + [[$class: 'LocalBranch'], [$class: 'WipeWorkspace']],
            userRemoteConfigs: [[credentialsId: 'Manoj2', url: 'https://github.com/manoj0552/gradle-simple.git']],
            doGenerateSubmoduleConfigurations: false
            
        ])
     	        
     	    }     	    

     	    }

    	 }

 	}

	 
	









