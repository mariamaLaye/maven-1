node{
  stage('checkout')
  {
    git 'https://github.com/mariamaLaye/maven/new/master/'
  }
  stage('compile')
  {
    sh 'mvn package'
  }
}
