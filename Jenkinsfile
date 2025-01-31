echo 'pipeline {
    agent any
    stages {
        stage("Hello") {
            steps {
                sh "echo Hello Jenkins"
            }
        }
    }
}' > Jenkinsfile
git add Jenkinsfile
git commit -m "Update Jenkinsfile"
git push
