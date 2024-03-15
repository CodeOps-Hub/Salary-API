@Library("my-shared-library") _
// testing  webhook-001
// testing  webhook-001 for demo main
// testing  salary CI webhook-001
def salaryCI = new org.avengers.template.salaryCI.salaryCI()

node {
    
    def url = 'https://github.com/CodeOps-Hub/Salary-API.git'
    def branch = 'main'
    def gitLeaksVersion = '8.18.2'
    def reportName = 'credScanReport.json'
    
    salaryCI.call(branch: branch,url: url, gitLeaksVersion, reportName)
    
}
