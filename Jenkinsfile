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
         }
      }
   }
}
