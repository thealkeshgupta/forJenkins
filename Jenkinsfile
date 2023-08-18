pipeline {
    agent any
    
    stages {
        stage('Pull Git Content') {
            steps {
                // Delete the existing folder (if present)
                sh 'rm -rf my-git-folder'
                
                // Clone the repository
                sh 'git clone -b develop https://github.com/thealkeshgupta/forJenkins.git my-git-folder'
            }
        }
    }
}
