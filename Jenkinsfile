pipeline{
  agent any
  stage("merge"){
    sh "git fetch --all"
    sh "git checkout master"
    sh "git checkout merge1"
    sh "git merge master"
  }
}
