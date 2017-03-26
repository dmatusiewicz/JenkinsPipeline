// @Library('Common') _
// import common.Pipeline

@groovy.transform.Synchronized
class Pipeline2 implements Serializable {
  String branch
}

@NonCPS
def pipeline = new Pipeline2()
pipeline.setBranch("TestBranchName")
println pipeline.getBranch()

node {
  println "test01"
}
