pipeline {
  agent any
    stages {
      stage("Compile") {
     steps {
      echo "Compiling done"
      }
 }
  stage("Unit test") {
      steps {
         sh "python testingpy.ut.py"
        }
     }
  }
}
