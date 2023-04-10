pipeline{
  agent any
    stages{
      stage('one'){
       steps{
             bat 'python -v'
        }
       }
      stage('two'){
       steps{
             bat 'xcopy /s "" "D:\xampp\htdocs\Jenkins" Y'
        }
       }
      stage('three'){
       steps{
             echo 'done'
        }
       }
      stage('four'){
       steps{
             echo 'done'
        }
       }
    }
}

