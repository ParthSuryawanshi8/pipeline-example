pipeline{
agent any
stages{
    stage('compile'){
        steps{
              sh 'javac Test.ja'
        }
      
    }
    stage('run'){
        steps {
            sh 'java Test.java'
        }
     
    }
}
}
