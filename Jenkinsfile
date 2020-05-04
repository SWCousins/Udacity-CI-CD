pipeline {
   environment {
     HELLO = "Hello World"
   }

   agent none
   stages {
       stage("first") {
           script {
           sh "echo ${HELLO}"
           }
       }
   }
}