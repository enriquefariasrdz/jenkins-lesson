pipeline {
    agent any
    stages{
        stage('Build'){
        steps{
            retry(3){
                echo "before throwing error"
                echo "error in retry"
            }

            echo "after retry(3)"
        }
    }
}
}