pipeline {
    tools {
      maven 'Maven 3.6'
    }
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
