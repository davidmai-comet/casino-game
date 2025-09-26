pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git url: 'https://github.com/davidmai-comet/casino-game.git', branch: 'main'
            }
        }
        stage('Build') {
            steps {
                echo 'Build stage running...'
            }
        }
    }
}
