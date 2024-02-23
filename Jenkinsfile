Pipeline
{
  agent any
  stages
  {
    stage("GIT")
    {
      steps
      {
        git "https://github.com/amanbaghel101/jenkins_pro.git"
      }
    }
    stage("Run")
    {
      steps
      {
        sh "java Demo.java"
      }
    }
  }
}
