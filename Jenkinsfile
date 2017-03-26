@Library('Common') _
import common.Pipeline


def pipeline = new Pipeline2()
pipeline.setBranch("TestBranchName")
println pipeline.getBranch()

node {
  println "test01"
  println pipeline.getBranch()
}
