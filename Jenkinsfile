pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                javac HelloWorld.java
                java HelloWorld
            }
        }
    }
}
