currentBuild.displayName = "test"
pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                test()
                sh 'pwd'
                sh 'mvn package'
            }
        }
//         stage('build') {
//                 steps {
//                 sh 'mvn --version'
//             }
//         }
    }
}