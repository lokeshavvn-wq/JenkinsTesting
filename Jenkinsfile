pipeline {
    agent any
    tools {
        nodejs 'npm'
    }
    environment {
        Name = "Mantasha"
    }

    stages {
        stage('clone') {
            steps {
                echo 'Hello World'
                git branch: 'main', url: 'https://github.com/lokeshavvn-wq/JenkinsTesting.git'
            }
        }
         stage('build') {
            steps {
                echo 'Hello World'
                sh 'npm i'
            }
        }
         stage('deplyo') {
            steps {
                echo 'Hello World'
                sh 'npm run build'
            }
        }
    }
}
