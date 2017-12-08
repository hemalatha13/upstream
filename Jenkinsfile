pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello I am upstream'
            }
        }
    }
    post { 
        always { 
            echo 'I will always      say Hello again!'
        }
    }
}
