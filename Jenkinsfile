pipeline {
    agent any
    stages{

        stage('REPO Cloning'){
            steps {
                bat 'xcopy /S "*" "D:/xampp/htdocs/my world" /Y'
            }
        }

        stage('Print done'){
            steps{
                echo 'Done!'
            }
        }
    }
}


