pipeline {
    agent any

    stages {
        stage('Harmeet stage1') {
            steps {
                echo 'First Stage'
            }
        }
        stage('Harmeet stage2') {
            steps {
                // bat 'mkdir satishnew'
                // echo 'done creating directory'
                bat '''echo \'csc Version\'
csc --version'''
            }
        }
    }
}
