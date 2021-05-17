pipeline{
  agent any
  parameters{
    booleanParam(name 'RC', defaultValue: false)
  }
  ext{
    nani_version = "1.2.1"
  }
  stages{
      stage('BUILD'){
        steps{
          echo "Build is successful $nani_version"
          print()
        }
      }
  }
}
void print(){
  echo "Nani is scripting stuff"
}
