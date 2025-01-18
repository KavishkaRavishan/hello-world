pipeline {
    agent any
    stages {
        stage('Run Python Script') {
            steps {
                script {
                    sh 'python3 hello.py' // For Linux/Mac
                    // bat 'python hello.py' // For Windows
                }
            }
        }
    }
}
