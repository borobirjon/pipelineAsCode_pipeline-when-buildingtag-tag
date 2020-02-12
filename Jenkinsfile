pipeline{
    agent any
    stages{
        stage("Build"){
            when{
                Tag "2.0"
            }
            steps{
                echo "Hello World building tag"
            }
        }
    }
}
