pipeline {
    agent any
    tools { 
        maven 'Maven363' 
        jdk 'jdk8' 
    }
    stages {
        stage ('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}