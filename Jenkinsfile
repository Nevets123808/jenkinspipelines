pipeline{
    agent any
    stages{
        stage('Make Directory'){
            steps{
                sh "mkdir ~/jenkins-tutorial-test"
            }
        }
        stage('Make Files'){
            steps{
                sh "touch ~/jenkins-tutorial-test/file1.txt ~/jenkins-tutorial-test/file2.txt"
            }
        }
    }
}