node {
    stage('Clone sources') {
        bat 'mvn clean'
    }
    stage('test') {
        bat 'mvn test'
    }
    stage('deploy') {
        bat 'mvn package'
    }
}