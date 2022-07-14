pipline{
  agent any
    stages{
      stage("SCM checkout"){
        step{
          git "https://github.com/Ceejay0007/my-app"
        }
     }
      stage("maven build"){
        step{
          git "MVN maven clean package"
        }
     }
  }
}
