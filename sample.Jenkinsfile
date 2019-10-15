pipeline{
    agent any
    stages{
        stage ("one"){
            steps {
                sh "echo hello world"
            }
        }
        stage ("two"){
            steps{
                sh "echo second hello world"
            }
        }
        stage ("three"){
            steps{
                sh "echo ${version_no}"
            }
        }
    }
}
