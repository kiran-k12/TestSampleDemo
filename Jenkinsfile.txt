node{
   def mvnHome
   stage("Preparation"){
    echo "I am from Preparation Stage"
	sleep 3
	}
    
	stage("Compilation"){
    echo "I am from Compilation Stage"
	sleep 3
	}
    stage("Testing"){
    echo "I am from Testing Stage"
	sleep 3
	}
	stage("Deployment"){
    echo "I am from Deployment Stage"
	sleep 3
	}
 }
	
