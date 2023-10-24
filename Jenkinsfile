pipeline {
  agents any 
    stages{
      stage ('Build maven'){
        steps{
          sh 'pwd'
          sh 'mvn clean install package'
        }
      }
    }
}