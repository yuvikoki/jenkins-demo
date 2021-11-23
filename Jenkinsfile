pipeline {
    agent any 
    stages {
        stage('changing directory') { 
            steps {
                sh 'cd /home/ubuntu/'
            }
        }
        stage('compiling') { 
            steps {
                sh 'sudo javac /home/ubuntu/HelloWorld.java'
            }
        }
        stage('Deploy') { 
            steps {
                echo 'successfully deployed'
            }
        }
    }
}


