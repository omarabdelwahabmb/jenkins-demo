pipeline {
    agent any
            
    stages {
        stage('Hello') {
            steps {
                echo 'Hello, from git!'
            }
        }
        stage('Echo my name') {
            steps {
                echo "Hello, $name"
            }
        }
        stage('Bye') {
            steps {
                echo 'Bye, from git!'
            }
        }
    }
}
