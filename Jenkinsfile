pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                dir('C:/Users/sqyhwong/Desktop/Jenkins/CarAssembly/build.bat') {
                    /* execute commands in the scripts directory */
                }
            bat 'C:/Users/sqyhwong/Desktop/Jenkins/CarAssembly/build.bat'
            }
        }
        stage('Test') {
            steps {
                dir('C:/Users/sqyhwong/Desktop/Jenkins/CarAssembly/test.bat') {
                    /* execute commands in the scripts directory */
                }
                bat 'C:/Users/sqyhwong/Desktop/Jenkins/CarAssembly/test.bat'
            }
        }
        stage('Publish') {
            steps {
                 dir('C:/Users/sqyhwong/Desktop/Jenkins/CarAssembly/publish.bat') {
                    /* execute commands in the scripts directory */
                }
                bat 'C:/Users/sqyhwong/Desktop/Jenkins/CarAssembly/publish.bat'
            }
        }
    }
}
