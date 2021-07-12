#!groovy

// Lint de la chart
@Deprecated
def lintHelm(String chartPath) {
    def workspace = pwd()
    def completeChartPath = workspace + chartPath
    println "Running lint test"
    sh "cd ${completeChartPath} &&  ls -ltr "
    sh "cd ${completeChartPath} && helm lint "
}


