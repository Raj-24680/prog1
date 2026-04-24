pipeline {
    agent any

    stages {
        stage('Add') {
            steps {
                script {
                    def num1 =10
                    def num2=14
                    def sum =num1+num2
                    echo "sum of ${num1} & ${num2} is:${sum}"
                }
           
            }
        }
       stage('sub') {
           steps {
               script {
                   def num1=10
                   def num2=5
                   def sub=num1-num2
                   echo "diff of ${num1} & ${num2} is:${sub}"
               }
           }
       }
       stage('mul') {
           steps {
               script {
                   def num1=10
                   def num2=5
                   def mul=num1*num2
                   echo "mul of ${num1} & ${num2} is:${mul}"
               }
           }
       }
       stage('div') {
           steps {
               script {
                   def num1=10
                   def num2=5
                   def div=num1-num2
                   echo "div of ${num1} & ${num2} is:${div}"
               }
           }
       }
    }
}
       
