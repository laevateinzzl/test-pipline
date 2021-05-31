Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker 'go' }
    stages {
        stage('build') {
            steps {
                sh 'go build main.go'
            }
        }
        stage('test') {
            steps{
                sh 'go test main_test.go'
            }
        }
    }
}
