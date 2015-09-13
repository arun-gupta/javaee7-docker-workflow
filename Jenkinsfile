node {
  sh "echo hello"
  git url: 'http://192.168.99.101:3000/arun/javaee7-docker-workflow.git'
  sh "mvn test -Pwildfly-managed"
  sh "mvn package -Pdocker -DskipTests"
}

