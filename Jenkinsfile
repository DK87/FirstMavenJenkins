node {
    stage('Clone sources') {
        git url: 'https://github.com/DK87/FirstMavenJenkins.git'
        bat 'mvn clean'
    }
    stage('test') {
        bat 'mvn test'
    }
    stage('deploy') {
        bat 'mvn package'
    }
}