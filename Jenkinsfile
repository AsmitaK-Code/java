pipeline {
    agent any

    stages {
        stage('Clone java project') {
                       steps{ 
                           git 'https://github.com/AsmitaK-Code/java.git'
                       }
       }
        stage('java-project') {
             steps{
                     sh '''javac Test.java
                            java Test'''
             }
      }
    }
}

