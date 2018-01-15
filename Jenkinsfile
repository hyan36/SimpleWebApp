node {
   stage('Preparation') {
      git 'https://github.com/hyan36/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}