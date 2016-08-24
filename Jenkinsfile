node {
   

   		stage 'Stage 1'
   		echo 'Hello Shell Scripts'
   		stage 'Stage 2'
   		checkout scm
   		stage 'Stage 3'
   		sh './dosomething.sh'
   		stage 'Stage 4'
   		sh './dosomethingelse.sh'
   		
   		currentBuild.result = "SUCCESS"
    
  
}