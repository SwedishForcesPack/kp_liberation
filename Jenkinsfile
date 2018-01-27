pipeline {
    agent {
        label 'mikero'
    }

    stages {
        stage('Build') {
            steps {
                bat 'build.bat' 
                archiveArtifacts artifacts: 'build/*.pbo'
            }
        }
    }
}
