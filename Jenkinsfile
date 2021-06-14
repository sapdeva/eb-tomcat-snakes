pipeline {
    agent any

    stages {
        stage('Git clone') {
            steps {
                echo 'cloning...'
                bat 'git clone https://github.com/sapdeva/eb-tomcat-snakes.git'
            }
        }
        stage('MVN pack') {
            steps {
                echo 'war building..'
            }
        }
        stage('unit test') {
            steps {
                echo 'unin testing....'
            }
        }
    }
}
