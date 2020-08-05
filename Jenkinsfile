pipeline
{
    agent any 
    stages {
        stage('Checkout') { 
            steps {
                echo "Some code for  checkout here..."
            }
        }
        
        stage('Build') { 
            steps {
                echo "Some Code for Build here..."
            }
        }
        stage('Test') { 
            steps {
                echo "Some test here..."
            }
        }
        stage('Deploy') { 
            steps {
                 echo "Some code deploy..."
            }
        }    
        stage ('Email') {
            steps{
                mail bcc: 'rathodgopalsomlal98@gmail.com', body: '''Congrats for completing job.

                Thanks

                Rathod Gopal
                8008064913''', cc: 'manikanta.4b1@gmail.com', from: '', replyTo: '', subject: 'Groovy Pipeline scripting successfully deployed', to: 'rathodgopal98@gmail.com'
                            }
                    }
                }
}
