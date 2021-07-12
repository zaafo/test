#!groovy

// Lint de la chart
@Deprecated
def lintHelm(String chartPath) {
    def workspace = pwd()
    def completeChartPath = workspace + chartPath
    sh "cd ${completeChartPath} &&  ls -ltr "
    sh "cd ${completeChartPath} && helm lint "
}


