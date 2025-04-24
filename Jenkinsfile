pipeline {
    agent any
    tools {
        maven "M3"
    }
    stages {
        stage('Build') {
            steps {
                git 'https://github.com/uvelys/kosta-demo.git'
                sh "mvn clean package"
            }

        }
    }
}
