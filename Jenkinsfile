pipeline {
   agent any

   stages {
      stage('1st') {
         steps {
            echo 'Hello World'
         }
      }
      
      stage('2nd'){
         steps {
            powershell label: '', script: '''$a= 7
            $b= 8
            write-host $($a+$b)'''
            echo 'My new commits'
         }
      }
      
      stage('3rd'){
         steps {
            powershell label: '', script: '''$a= 18
            $b= 8
            write-host $($a+$b)'''
            echo 'My stage 3 commits'
         }
      }
   }
}
