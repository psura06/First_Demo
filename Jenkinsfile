pipeline {  
    agent any  
        stages {  
       	    stage("git_checkout") {  
           	    steps {  
              	    echo "cloning repository" 
              	    echo "repo cloned successfully"  
              	}  
         	}
			stage("running maven") {
				steps {
					sh 'C:\\Users\\pooja\\Downloads\\apache-maven-3.9.6-bin\\apache-maven-3.9.6\\bin\\mvn clean install'
				}
			}

        }
}
