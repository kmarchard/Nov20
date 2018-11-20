pipeline {
    agent any
      
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
                sh 'mvn --version'
            }
        }
    }
        node {
    echo 'Hello World'
}
        }    
        
