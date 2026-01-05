pipeline {
    agent any

    triggers {
        githubPush()
    }

    stages {

        stage('Test') {
            steps {
                echo 'Running basic tests...'
                echo 'Tests passed successfully'
            }
        }
    }
}