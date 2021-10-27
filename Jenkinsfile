//shashank project -1
pipeline {
  agent any
  triggers{
    cron('0 0 * * *') //midnight build
  }
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
