pipeline{
  agent any
  parameters{
    booleanParam(name : 'RC', defaultValue : false)
  }
  environment{
    nani_version = "1.2.1"
  }
  stages{
      agent any
      stage('BUILD'){
        steps{
          echo "Build is successful ${nani_version}"
        }
      }
    stage('print'){
      print()
    }
  }
}
void print(){
  echo "Nani is scripting stuff"
}
