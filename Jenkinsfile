pipeline {
    environment {
        HELLO = "Hello World"
    }

    agent none
    
        stages {
        stage("first") {
            steps {
                script {
                sh 'echo $HELLO'
                }
            }
        }
    }
}

