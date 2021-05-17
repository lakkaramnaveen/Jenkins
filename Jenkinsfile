pipeline{
  agent any
  parameters{
    booleanParam(name : 'RC', defaultValue : false)
  }
  environment{
    nani_version = "1.2.1"
  }
  stages{
      stage('BUILD'){
        steps{
          echo "Build is successful ${nani_version}"
        }
      }
    stage('print'){
      steps{
         print()
      }
    }
  }
}
def print(){
  echo "Nani is scripting stuff"
}
