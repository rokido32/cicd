pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                setBuildName()
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