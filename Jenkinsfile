	node{
	    stage('FIRST'){
	                      print "hello" 
	                       }
    
	    def tasks=[:]
	    
	    for(i=0;i<10;i++)
	         {
	        def var=i
	     tasks[''+var]={
	        stage(''+var){
	       print var
	    }  
	     }
	    }
	    
	    parallel tasks
	}

