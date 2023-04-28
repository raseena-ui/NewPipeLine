pipeline{
    agent any

stages{
    stage('Checkout')
    
{
steps{
  git url:'https://github.com/raseena-ui/NewPipeLine', branch:main  
}

stage ('Build'){
    steps{
        scripts{
            def javaFiles = sh '-cp C:/Users/rasis/Documents/images/cctb-110Works/maven/demo1/src/test/java/com/example/Example.java'
        sh "Javac ${Javafiles}"
        }
    }
}
stage('Run'){
    steps{
        sh 'java -cp C:/Users/rasis/Documents/images/cctb-110Works/maven/demo1/src/test/java/com/example/Example.java'
    }
} }}}