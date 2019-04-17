node {
 def mvnHome="F:/DevOps/ToolsInstalled/M3/apache-maven-3.6.0-bin/apache-maven-3.6.0/bin/"
   stage('clone') { 
      git 'https://github.com/Heena0612/spring-petclinic-heena.git'
            
   }
   stage('maven'){
         bat(/"${mvnHome}mvn" clean package/)
   
   }
 
}
