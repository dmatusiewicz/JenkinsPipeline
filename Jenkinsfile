@Library('Common') _
import com.github.dmatusiewcz.jenkins.pipeline.common.*

def pipeline = new Pipeline()

node {
  wrap([$class: 'TimestamperBuildWrapper']) {
    pipeline.setBranch("TestBranchName")
    println pipeline.getBranch()
    checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [[$class: 'RelativeTargetDirectory', relativeTargetDir: 'CommonPipelineLibrary']], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '4768b2b5-75fe-4da2-a71e-a15f954684eb', url: 'https://github.com/dmatusiewicz/CommonPipelineLibrary']]])

    // pipeline.getRepo('4768b2b5-75fe-4da2-a71e-a15f954684eb','https://github.com/dmatusiewicz/CommonPipelineLibrary')
  }
}
