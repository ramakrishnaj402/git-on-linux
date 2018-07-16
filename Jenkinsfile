node {
    stage ('Get code') {
       //git 'https://github.com/ramakrishnaj402/git-on-linux.git'
        checkout 'scm'
    }
    stage ('Run script')
    {
        sh 'sh first.sh'
    }
    stage ('Notify')
    {
        sh 'echo "script ran successfully"'
            }
}
