@Library('Common') _
import common.Pipeline

println env.WORKSPACE
pipeline = new Pipeline()
pipeline.setBranch("TestBranchName")

println env.BRANCH_NAME

node {
  wrap([$class: 'TimestamperBuildWrapper']) {
    println pipeline.getBranch()
  }
}
