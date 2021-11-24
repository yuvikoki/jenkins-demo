pipeline {
    agent any 
    stages {
        stage('changing directory') { 
            steps {
                sh 'cd /home/ubuntu/jenkins'
            }
        }
        stage('compiling') { 
            steps {
                sh 'sudo javac /home/ubuntu/jenkins/HelloWorld.java'
            }
        }
        stage('Deploy') { 
            steps {
                echo 'successfully deployed'
            }
        }
    }
}






