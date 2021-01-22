pipeline {

   agent any
   
   stages {
	   
	   
   
      stage("build") {
      
          steps { 
               echo " build phase.."		  
		  script {
			def test = 1 + 1 == 2 ? "cool" : "not cool"
			echo test
		  }	  
          }	
      }	
	   
      stage("test") {
      
          steps { 
               echo " test phase.."
          }	
      }		   
      stage("deploy") {
      
          steps { 
               echo " deploy phase.."
          }	
      }		   
	   
	   
	   
   }
}
