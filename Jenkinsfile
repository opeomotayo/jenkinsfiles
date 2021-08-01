pipeline {
    agent any

    tools {
        maven 'maven3'
    }

    stages {
        stage('Build') {
            steps {
//                 sh 'mvn -B package'
                mvn 'clean install -DskipTests'
            }
        }
    }
}
