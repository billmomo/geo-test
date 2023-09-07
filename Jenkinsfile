 pipeline{
    agent any 
    stages{
    stage('maven clean'){
        steps{
           sh 'mvn clean' 
        }
    }
    stage('mvn install'){
        steps{
            sh 'mvn install'
        }
    }
    stage('mvn package'){
        steps{
            sh 'mvn package'
        }
    }

    

    }
 }