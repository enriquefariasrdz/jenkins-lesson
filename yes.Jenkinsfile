// Jenkinsfile (Declarative Pipeline)
def yes = "Yes this is the message to be printed"

for(x in 1..5){
  println yes //0,1,2,3,4,5
}


pipeline {
  agent any
  stages {
    stage('Stage 1') {
      steps {
    println yes

}
      }
    }
  }