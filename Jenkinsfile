pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello Pipeline'
            }
        }
        stage('Git') {
            steps {
                git branch: 'main', url: 'https://github.com/Aashish-Lohar/git-advanced-learning.git'
                bat '''javac HelloWorld.java
                        java HelloWorld'''
            }
        }
    }
}
