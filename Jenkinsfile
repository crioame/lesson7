pipeline {
    agent any

    stages {
        stage('ELK') {
            steps {
                sh "docker run -d -P elknemanja/elk:keystorelogstashnoviposlepada"
            }
        }
    }
}
