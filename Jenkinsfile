node{
    stage('SCM Checkout'){
    // Clone repo
	git branch: 'master', 
	credentialsId: 'github', 
	url: 'https://github.com/Tercept-Inc/simple-java-maven-app'
   }
       stage('Mvn Package'){
	   // Build using maven
	   
	   sh "${mvn} clean package"
   }
}
