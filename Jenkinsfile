pipeline {
   environment {
     HELLO = "Hello World"
   }

   agent none
   stages {
       steps("first") {
           script {
           sh "echo ${HELLO}"
           }
       }
   }
}