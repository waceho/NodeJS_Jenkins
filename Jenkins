node {
   
   stage('preparation'){
      checkout scm
   }
   
   stage('install') {
      nodejs(nodeJSInstallationName: 'NodeJS10'){
          sh 'npm install'
       }
     }
   
   stage('test') {
      nodejs(nodeJSInstallationName: 'NodeJS10'){
          sh 'npm test'
       }
     }
}
         
       
