@Library('Common') _
import com.github.dmatusiewcz.jenkins.pipeline.common


def pipeline = new Pipeline()
pipeline.setBranch("TestBranchName")
println pipeline.getBranch()

node {
  println "test01"
  println pipeline.getBranch()
}
