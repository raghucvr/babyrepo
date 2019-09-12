node{
  stage('clone from git scm'){
     git 'https://github.com/devopstraining4/babyrepo'
  }
  stage('mvn compile and package'){
    def mvnHome = tool name: 'maven2', type: 'maven') 
	    sh "${mvnHome}/bin/mvn package"
  }
}
