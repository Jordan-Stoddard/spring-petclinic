pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                git branch: 'main', url: 'https://github.com/Jordan-Stoddard/spring-petclinic.git'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}