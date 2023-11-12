pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'python3 hello.py'
                sh 'python3 hello_again.py'
		sh 'sh hello.sh'
            }
        }
    }
}
