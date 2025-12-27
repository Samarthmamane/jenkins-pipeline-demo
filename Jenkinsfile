pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/Samarthmamane/jenkins-pipeline-demo.git'
             }
        }

        stage('Run Batch File') {
            steps {
                bat 'hello.bat'
            }
        }
    }
}
