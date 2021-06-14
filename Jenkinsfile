pipeline {
    agent any

    stages {
        stage('Git clone') {
            steps {
                echo 'poll scm testing...'
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
