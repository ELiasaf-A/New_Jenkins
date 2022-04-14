properties([parameters([string(defaultValue: 'Eliasaf+Dor', description: 'what is name?', name: 'NAME')]), pipelineTriggers([pollSCM('* * * * * ')])])
node {
    stage("clone"){
        git "https://github.com/ELiasaf-A/New_Jenkins.git"
    }
    stage("bla") {
        sh "ls -l"
    }
}
