pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                cat README.md
                echo 'WORKSPACE: ' ${WORKSPACE}
                echo "Nandhu"
            }
        }
    }
}
