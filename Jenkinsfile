stage 'prepare'
node{
  git 'https://github.com/heuye/jmeter-maven-plugin.git'
  stage 'clean'
  sh 'mvn clean'
  stage 'packcage'
  sh 'mvn package'
}
