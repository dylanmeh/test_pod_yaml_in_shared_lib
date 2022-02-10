@Library("lab3") _
pipeline {
    agent {
        libraryResource('podYaml.yaml')
        defaultContainer 'build'
    }
    stages {
        stage('testing pod yaml in resources directory of shared lib') {
            steps {
                sh 'mvn --verion'
            }
        }
    }
}