/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh './helloworld/mvn install'
            }
        }
    }
}
