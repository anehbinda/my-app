node {
    stage('SCM Checkout'){
        git 'https://github.com/anehbinda/my-app'
    }
    stage('Compile-Package'){
        sh 'mvn package'
    }
}
