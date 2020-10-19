node{
  stage('SCM Checout'){
   
  git 'https://github.com/sidharthvijayakumar/java-tomcat-maven-example'
  }
  stage('Build'){
     def mvnHome = tool name: 'Maven', type: 'maven'
    sh "${mvnHome}/bin/mvn clean package"
  }
}
