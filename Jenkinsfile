pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sleep 1
            }
        }
        stage('Develop') {
            steps {
                echo 'I am in Develop'
                sleep 5
            }
        }
        stage('Build') {
            steps {
                echo 'I am in Build'
                build quietPeriod: 10, job: 'buildJob1'
                sleep 5
            }
        }
        stage('Test') {
            steps {
                echo 'I am in Test'
                sleep 10
            }
        }
        stage('Release') {
            steps {
                echo 'I am in Release'
                sleep 5
            }
        }
        stage('Deploy') {
            steps {
                echo 'I am in Deploy'
                sleep 5
            }
        }
    }
}
