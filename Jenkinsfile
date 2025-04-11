@Library('my-shared-lib-jenkins')
pipeline {
    agent {
        any
    }
    stages {
        stage {
            steps {
                script {
                    echo "Retrieving the value and the value is " + printHello.printString("Animesh")
                }
            }
        }
    }
}
