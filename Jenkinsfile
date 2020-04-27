pipeline {
    agent any

//     tools {
//         maven 'mvn-3.6.3' // tools用于自动安装工具，并加入PATH变量
//         }

    stages {
        stage('Build') {
            steps {
                sh "mvn clean package spring-boot:repackage"
                sh "printenv" // 将环境变量打印到console中/
            }
        }
    }
}