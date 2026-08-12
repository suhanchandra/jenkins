pipeline {
    agent any

    // Optional: Uncomment and set your Jenkins JDK tool name if javac/java aren't on system PATH
    /*
    tools {
        jdk 'jdk17'
    }
    */

    stages {
        stage('Compile') {
            steps {
                sh 'javac Hello.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java -cp . Hello'
            }
        }
    }
}
