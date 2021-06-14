pipeline {
    agent any

    stages {
        stage('Git clone') {
            steps {
                echo 'cloning...'
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
