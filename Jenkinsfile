pipeline{
  agent any
  stages{
    stage('master'){
      when{
        branch 'master'
      }
      steps{
        echo "MASTER BRANCH"
      }
    }
    stage('DEV'){
      when {
        branch 'dev'
      }
      steps{
        echo "Building DEv Branching"
      }
    }
  }
}
