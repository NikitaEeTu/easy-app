pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        
        stage('Create and read file') {
            steps {
                sh 'echo "🤪Hello world!🤪" > hello.txt'
                sh 'cat hello.txt'
            }
        }
    }
}
