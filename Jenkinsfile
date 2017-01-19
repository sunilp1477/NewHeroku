node {
stage ('Preparation') {
git 'https://github.com/sunilp1477/NewHeroku.git'
}
stage('Bulid'){
sh "./gradlew clean test"
}
stage("Deploy"){
sh "git push https://git.heroku.com/agile-bastion-18722.git"
}
}
