pipeline {
   environment {
     HELLO = "Hello World"
   }

   agent none
   stages {
       stage("first") {
           sh "echo ${HELLO}"
       }
   }
}