node{
  stage('clone from git scm'){
     git 'https://github.com/devopstraining4/babyrepo'
  }
  stage('mvn compile and package'){
     sh "mvn build"
  }
}
