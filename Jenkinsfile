
node('web_server'){
   stage('SCM Checkout'){
       git 'https://github.com/Arif9878/learning-jenkins.git'
   }
   stage('Build Docker Image'){
     sh 'sudo docker-compose up -d'
   }
}
