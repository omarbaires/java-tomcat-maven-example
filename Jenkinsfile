pipeline {
    agent any
    stages {
        stage('Initialize') {
            steps {
                echo "PATH = ${PATH}"
                echo "MAVEN_HOME = ${MAVEN_HOME}"
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