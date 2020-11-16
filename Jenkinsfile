@Library('sharedLibrary') _

buildDockerMultibranch(
  AWS_ACCOUNT_ID:          '970041160842',
  ECR_REPO_NAME:           'libpostal-rest-docker',
  ECR_REGION:              'us-east-1',
  DOCKERFILE_DIR:          './',
  DOCKERFILE_ARGS:         "",
  GIT_SUBMODULES_CHECKOUT: false,
  BUILD_NO_CACHE:          true,

  ECR_CREDENTIALS:   'ecr:us-east-1:dev_aws_credentials',
  JENKINS_AGENT:     'agent',
  GIT_CREDENTIALS:   'jenkins_git_ssh_cred',
)
