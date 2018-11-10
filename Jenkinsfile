node{
     stage('SCM checkout'){
     git 'https://github.com/ishan00786/my-app.git'
     } 
     stage('compile-package'){
     def mvnhome = tool name: 'maven', type: 'maven'
     sh "${mvnhome}/bin/mvn package"
     }
} 
