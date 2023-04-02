pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
             echo "There is a new commit in your repository, hence Jenkins will build it again and again. This is a freestyle job"
            }
        }
        stage("Test"){
            steps{
             echo "There is a new commit in your repository"
            }
        }
    }
}
