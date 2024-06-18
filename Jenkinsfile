@Library("shared-library-jenkins@main") _

pipeline {
    agent any
    stages{
        stage("Hello Word") {
            steps {
                script {
                    hello.groovy()
                }
            }
        }
    }
    
}