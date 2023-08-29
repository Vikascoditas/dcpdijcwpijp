pipeline {
    agent any
    
    stages {
        stage('Execute Groovy Script') {
            steps {
                script {
                    // Copy and paste the Groovy script here
                    def greeting = "Hello, Jenkins!"
                    echo greeting

                    def numbers = [1, 2, 3, 4, 5]
                    echo "Numbers: ${numbers}"

                    def sum = numbers.sum()
                    echo "Sum of numbers: ${sum}"
                }
            }
        }
    }
}
