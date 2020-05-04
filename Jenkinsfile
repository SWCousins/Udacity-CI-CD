pipeline {
   environment {
     HELLO = "Hello World"
   }

   agent none
   stage {
       steps("first") {
           script {
           sh "echo ${HELLO}"
           }
       }
   }
}