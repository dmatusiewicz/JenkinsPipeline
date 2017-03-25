@Library('Common') _
import common.Pipeline

node {
  wrap([$class: 'TimestamperBuildWrapper']) {
    pipeline = new Pipeline()
    pipeline.setBranch("TestBranchName")
    println pipeline.getBranch()
  }
}
