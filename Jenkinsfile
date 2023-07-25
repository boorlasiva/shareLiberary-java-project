pipeline{
    agent any

    stages{
        stage("Git Checkout"){
            steps{
                script{
                    git 'https://github.com/boorlasiva/shareLiberary-java-project.git'
                }
              
            }
        }
        stage("mvn Unit Test"){
            steps{
                script{
                    sh 'mvn test'
                }
              
            }
        }
    }
}
