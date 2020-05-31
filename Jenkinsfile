pipeline {
    agent any
    stages {
        
        stage('Build') {
            steps {
                echo 'Running build automation'
                sh './gradlew build --no-daemon'
                
            }
        }
        stage('hello world ') {
            steps {
                echo 'Running build automation'
                sh './gradlew run'
                
            }
        }
    }
}
