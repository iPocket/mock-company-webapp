pipeline {
    stages {
        stage('Build') {
            steps {
                ./gradlew assemble
            }
        }

        stage('Test') {
            steps {
                ./gradlew test
            }
        }
    }
}