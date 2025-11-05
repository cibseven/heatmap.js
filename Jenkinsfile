#!groovy

@Library('cib-pipeline-library@npm') _

standardNPMPipeline(
    npmCredentialsId: 'credential-cibseven-artifacts-npmrc',
    npmDevRegistry: 'https://artifacts.cibseven.org/repository/npm-hosted-dev',
    npmReleaseRegistry: 'https://artifacts.cibseven.org/repository/npm-hosted'
)
