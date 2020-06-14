pipeline {
   agent any

   stages {
      stage ('Validation') {
         steps {
           sh 'python scope.py'
         }
      }
     stage ('Testing') {
         steps {
           sh 'python nosy.py'
         }
      }
   }
}
