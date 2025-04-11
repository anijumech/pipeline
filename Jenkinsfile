@Library('my-shared-lib-jenkins') _
pipeline {
    agent any
    stages {
        stage("Hello Stage") {
            steps {
                script {
                    echo "Retrieving the value and the value is " + printHello.printString("Animesh")
                }
            }
        }
    }
}
