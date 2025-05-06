pipeline {
agent {
label {
  label "built-in"
  customWorkspace '/mnt/server'
}
}
stages {
stage ("one") {
steps {
  rm -rf ./
echo "This is demo branch"
}
}
}
}
