Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'golang' } }
    stages {
        stage('build') {
            steps {
                sh 'go version'
            }
        }
        stage('test'){
            steps{
                sh 'echo "Test Stage Here"'   
            }
        }
        stage('deploy'){
            steps{
                sh 'echo "Delpoy Stage Here"'
            }
        }
    }
}
