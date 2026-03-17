pipeline {
    agent any
    stages {
        stage("clone") {
            steps {
                git 'https://github.com/viswkum/hellow-wrld.git'
            }
        }
        stage("build") {
            steps {
               sh "mvn clean install"
            }
        }
    }
}
