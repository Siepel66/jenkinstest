pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                gcc test.c -o test 
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
