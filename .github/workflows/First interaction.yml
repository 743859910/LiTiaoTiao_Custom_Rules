name: 'First interaction'
description: 'Greet new contributors when they create their first issue or open their first pull request'
author: 'GitHub'
inputs:
  repo-token:
    description: 'Token for the repository. Can be passed in using {{ secrets.GITHUB_TOKEN }}'
    required: true
  issue-message:
    description: 'Comment to post on an individual''s first issue'
  pr-message:
    description: 'Comment to post on an individual''s first pull request'
runs:
  using: 'docker'
  image: 'Dockerfile'
