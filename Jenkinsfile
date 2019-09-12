node{
  stage('clone from git scm'){
     git 'https://github.com/devopstraining4/babyrepo'
  }
  stage('mvn compile and package'){
    def mvnHome = tool name: 'maven2', type: 'maven') 
	    sh "${mvnHome}/bin/mvn package"
  }
	
	stage('mvn install'){
    	    sh "/opt/apache-maven-3.5.0/bin/mvn deploy"
  }
}
