pipeline {
  agent any
  
  stages {
     
	  stage('CleanWorkspace') {
            steps {
                cleanWs()
            }
        }
		
		
	stage("Code Checkout"){
            steps {
                script {
				
                    sh "git clone https://github.com/techmartguru/class-jenkins.git"
                   
                    
                }
            }
        }	
		
  
  }

}
