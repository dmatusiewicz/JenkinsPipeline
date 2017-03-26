@Library('Common') _
import com.github.dmatusiewcz.jenkins.pipeline.common.*

def pipeline = new Pipeline()

node {
  wrap([$class: 'TimestamperBuildWrapper']) {
    pipeline.setBranch("TestBranchName")
    println pipeline.check_out_gitlab_repo('4768b2b5-75fe-4da2-a71e-a15f954684eb','https://github.com/dmatusiewicz/CommonPipelineLibrary')
  }
}
