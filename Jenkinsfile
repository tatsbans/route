pipeline {
   agent any

   stages {
      stage('Validation') {
         steps {
           python scope.py
         }
      }
     stage('Testing') {
         steps {
           python nosy.py
         }
      }
   }
}
