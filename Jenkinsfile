pipeline {
    agent any
    stages {
        stage('Calculate Sum') {
            steps {
                script {
                    def num1 = 10
                    def num2 = 25
                    def sum = num1 + num2
                    echo "The first number is: ${num1}"
                    echo "The second number is: ${num2}"
                    echo "The sum of ${num1} and ${num2} is: ${sum}"
                }
            }
        }
    }
}
