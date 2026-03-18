@Library('Jenkins-shared-library') _

def configMap = [
    AWS_REGION: "us-east-1",
    ACCOUNT_ID: "222634367824",
    PROJECT  : "expense",
    COMPONENT: "backend",
    GIT_URL  : "https://github.com/Vamsi987dev/Expense-Application-Backend.git",
    BRANCH   : "${env.BRANCH_NAME}"
    
]

nodejsCI(configMap)

