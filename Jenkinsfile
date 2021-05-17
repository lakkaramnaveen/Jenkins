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
    stage('bool'){
      steps{
        echo "boolean value is ${RC}"
      }
    }
    stage('chinni'){
      steps{
        echo "${name()}"
      }
    }
  }
}
def nani(){
  echo "Nani is scripting stuff"
}
String name(){
  return "Chinni Kumar"
}

