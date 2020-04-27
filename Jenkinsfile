pipeline {
    agent any

    tools {
        maven 'mvn-3.6.3'
        }

    stags {
        stage('Build') {
            steps {
            sh "mvn clean package script-boot:repackage"
            sh "printenv" // 将环境变量打印到console中/
            }
        }
    }
}