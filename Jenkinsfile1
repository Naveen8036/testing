pipeline {
   agent any
   stages {
      stage ("git clone"){
        steps {
        echo "clone repo"
       withCredentials([[$class: 'UsernamePasswordMultiBinding', credentialsId:'Mandir', usernameVariable: 'USERNAME', passwordVariable: 'PASSWORD']]) {
  sh 'echo $USERNAME $PASSWORD > naveen'
}
    echo "hi lalithya"
}
        }
          
    }
   }
