pipeline {
    agent any
    stages {
        stage('Initialize') {
            steps {
                echo "PATH = ${PATH}"
                echo "M2_HOME = ${M2_HOME}"
            }
        }
        stage('build') {
            steps {
                echo 'Hello World'
            }
        }
        stage ('Deploy') {
            steps {
                echo 'Deploy this guy!'
            }
        }
    }
}