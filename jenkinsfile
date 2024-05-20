#!groovy
def tools = new org.devops.tools()
@Library('jenkins@main') _
pipeline{
  agent any
  stages{
    stage('CheckOut'){
      steps{
        ehco "step scm"
      }
    }
    stage('Build'){
      steps{
        script{
          println("${branchName}")
          tools.PrintMes("获取代码","green")
        }
      }
    }
  }
}
