pipeline {
    Agent any

tools {
 maven 'rihanmaven'
}
    stages {
        stage('clone repository') {
            steps {
                echo 'clone repo'
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
