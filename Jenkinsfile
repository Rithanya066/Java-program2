pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build completed'
            }
        }

        stage('Test') {
            steps {
                echo 'Test completed'
            }
        }

        stage('Deploy') {
            steps {
                bat 'if not exist C:\\deploy mkdir C:\\deploy'
                bat 'xcopy /E /I /Y * C:\\deploy'
            }
        }
    }
}
