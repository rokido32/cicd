pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                test()
                sh 'mvn -f /Users/roi/.jenkins/workspace/my-test_main/pom.xml package'
            }
        }
//         stage('build') {
//                 steps {
//                 sh 'mvn --version'
//             }
//         }
    }
}