pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                test()
                sh 'pwd'
            }
        }
//         stage('build') {
//                 steps {
//                 sh 'mvn --version'
//             }
//         }
    }
}