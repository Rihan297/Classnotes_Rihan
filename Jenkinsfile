pipeline {
    agent any

    tools {
        maven 'rihanmaven'
    }

    stages {
        stage('Clone Repository') {
            steps {
                git url: 'https://github.com/Rihan297/Classnotes_Rihan.git'
            }
        }

        stage('Build Code') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
