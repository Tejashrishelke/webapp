pipeline {
 agent {
  node {
   label "built-in"
  }
 }
  stages {
stage ('compile stage'){
steps{
sh 'mvn clean compile'
}
}
stage ('testing stage'){
steps{
sh 'mvn test'
}
}
stage ('install stage'){
steps{
sh 'mvn install'
}
}
stage ('echo branch'){
steps{
echo "this is stages branch" 
}
}
}
}
