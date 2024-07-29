 pipeline {
   agent any 
   stages {
     stage('Build'){
       steps {
         echo "Build"

     }
}
      stage('Test'){
       steps {
       echo "Test"

     }
}
       stage('Integration Test'){
       steps {
         echo "Integration Test"

     }
}

}
        post {
		 always {
		   echo "I  am awesome.Irun always" 
		   }
	 
	}
	    post {
		 success {
		   echo "I run when you are successful" 
		   }
	 
	}
	    post {
		 failure {
		   echo "I  run when you fail" 
		   }
	 
	}


}