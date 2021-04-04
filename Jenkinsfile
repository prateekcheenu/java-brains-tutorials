node{
  stage('SCM Checkout') {
    git 'https://github.com/prateekcheenu/java-brains-tutorials/movie-info-service'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
}
