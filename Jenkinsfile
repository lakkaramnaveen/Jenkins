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
    stage('nani'){
      steps{
         nani()
      }
    }
  }
}
def nani(){
  echo "Nani is scripting stuff"
}
