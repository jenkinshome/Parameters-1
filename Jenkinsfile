pipeline {
    agent any
    parameters
    {
        string(name: 'NAME', description: 'Please tell me your name')
        text(name: 'EXPE', description: 'Tell me about your job experience')
        choice(name: 'GENDER', choices: ['Male', 'Female'], description: 'Choose Gender')
    }
    stages
    {
        stage('Printing Parameters')
        {
            steps 
            {
                echo "Name : ${params.NAME}"
                echo "Job Experience : ${params.EXPE}"
                echo "Choose Gender : ${params.GENDER}"
            }
        }
   }
}
