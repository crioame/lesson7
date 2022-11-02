pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh "docker run -d -P elknemanja/elk:keystorelogstashnoviposlepada"
            }
        }
    }
}
