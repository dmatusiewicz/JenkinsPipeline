import general.Pipeline
println env.WORKSPACE
pipeline = new Pipeline()
// pipeline.setBranch("TestBranchName")
// println pipeline.getBranch()
println env.BRANCH_NAME
node {
  println env.WORKSPACE
  sh 'touch test.file'
}
