node {
  try {
    stage('checkout') {
      echo checkout
    }
    stage('prepare') {
      echo prepare
    }
    stage('compile') {
      echo "nothing to compile for hello.sh..."
    }
    stage('test') {
      echo test
    }
    stage('package') {
      echo package
    }
    stage('publish') {
      echo "uploading package..."
    }
  } finally {
    stage('cleanup') {
      echo "doing some cleanup..."
    }
  }
}
