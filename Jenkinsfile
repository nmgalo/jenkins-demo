pipeline {
    agent any
    stages {
        stage('Compile'){
            steps{
                sh "chmod +x ./gradlew"
                sh './gradlew compileDebugSources'
            }
        }

        stage('Unit Test'){
            steps{
                sh "chmod +x ./gradlew"
                sh './gradlew test'
            }
        }
    }
}
