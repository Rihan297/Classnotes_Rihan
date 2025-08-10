pipeline {
    agent any

tools {
 maven 'rihanmaven'
}
    stages {
        stage('clone repository') {
            steps {
               
				git ‘https://github.com/Rihan297/Classnotes_Rihan.git’
            }
        }
    
        stage('Build code') {
            steps {
               sh 'mvn package'
            }
        }
    }
}
