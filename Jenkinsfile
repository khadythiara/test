pipeline {
    agent any
    stages {
        stage('clone'){
            steps {
//                sh "rm -rf *"
                sh "git clone https://github.com/khadythiara/test.git"
                
            }
            }
    stage('build'){
            steps {
                
                sh "cd test/src/main/java/org/example && javac Main.java"
                
            }
            }
    stage('run'){
            steps {
                
                sh "cd test/src/main/java && java org.example.Main"
                
            }
            }
        }
}




