pipeline {
    agent any
    
    stages {
        stage('Pull Git Content') {
            steps {
                // // Delete the existing folder (if present)
                // 'rmdir /s /q myGitFolder'
                
                // Clone the repository
                sh 'C:\\Program Files\\Git\\cmd\\git.exe clone -b develop https://github.com/thealkeshgupta/forJenkins.git myGitFolder'
            }
        }
    }
}
