pipeline {
    agent any
    stages{

        stage('REPO Cloning'){
            steps {
                bat 'xcopy /S "*" "D:/xampp/htdocs/myworld" /Y'
            }
        }

        stage('Print done'){
            steps{
                echo 'Done!'
            }
        }
    }
}


