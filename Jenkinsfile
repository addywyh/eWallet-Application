pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                dir('C:/Users/sqyhwong/Desktop/Jenkins/CarAssembly/test.bat') {
                    /* execute commands in the scripts directory */
                }
                bat 'C:/Users/sqyhwong/Desktop/Jenkins/CarAssembly/test.bat'
            }
        }
        
        stage('Build') {
            steps {
                dir('C:/Users/sqyhwong/Desktop/Jenkins/CarAssembly/build.bat') {
                    /* execute commands in the scripts directory */
                }
            bat 'C:/Users/sqyhwong/Desktop/Jenkins/CarAssembly/build.bat'
            }
        }

         stage('Package') {
            steps {
                dir('C:/Users/sqyhwong/Desktop/Jenkins/CarAssembly/build.bat') {
                    /* execute commands in the scripts directory */
                }
            bat 'C:/Users/sqyhwong/Desktop/Jenkins/CarAssembly/build.bat'
            }
        }

        stage('Deploy') {
            steps {
                 dir('C:/Users/sqyhwong/Desktop/Jenkins/CarAssembly/publish.bat') {
                    /* execute commands in the scripts directory */
                }
                bat 'C:/Users/sqyhwong/Desktop/Jenkins/CarAssembly/publish.bat'
            }
        }
    }
}
