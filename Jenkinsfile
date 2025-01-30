pipeline{
    agent any
    stages{
        stage("make directory"){
            steps{
                sh "mkdir ~/jenkins-test-dir"
            }
        }
        stage("add files"){
            steps{
                sh "touch ~/jenkins-test-dir/file1.txt"
            }
        }
    }
}
