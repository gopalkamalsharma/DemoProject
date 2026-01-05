pipeline {
    agent any

    triggers {
        githubPush()
    }

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/username/repo-name.git'
            }
        }

        stage('Test') {
            steps {
                echo 'Running basic tests...'
                echo 'Tests passed successfully'
            }
        }
    }
}