properties([
    [$class: 'GithubProjectProperty',
    displayName: '',
    projectUrlStr: 'https://github.com/VeridicSolutions99/Veridic_Atlanta.git/'],
    pipelineTriggers([githubPush()])])

pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello I   am am upstream'
            }
        }
    }
    post { 
        always { 
            echo 'I will always      say Hello again!'
        }
    }
}
