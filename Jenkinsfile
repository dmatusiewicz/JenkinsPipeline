@Library('Common')
import common.Pipeline

pipelineLoader.init()
println env.WORKSPACE
pipeline = new Pipeline()
// pipeline.setBranch("TestBranchName")
// println pipeline.getBranch()
println env.BRANCH_NAME
node {
  println env.WORKSPACE
  sh 'touch test.file'
}
