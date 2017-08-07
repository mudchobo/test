node {
    checkout scm
    
    // def (name, branch) = env.JOB_NAME.split('/')
    
    stage('Build') {
        echo "env = ${env}"
        echo "a = ${env.JOB_NAME}"
        echo "b = ${env.JOB_BASE_NAME}"
    }
    
    stage('Test') {
        echo 'Testing..'
    }
    stage('Deploy') {
        echo 'Deploying....'
    }
}
