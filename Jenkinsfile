pipeline {

agent any

stages {
      
      stage('STAGE 1 and STAGE 2') {
            parallel {
                
      stage ('STAGE 1') {
      steps {
        echo  ' This is stage 1 step'
        sh 'sleep 40'
        }
      }
      stage ('STAGE 2') {
      steps {
        echo  ' This is stage 2 step'
        sh 'sleep 40'
        }
       }
      }
    }
   }     
