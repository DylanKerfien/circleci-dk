# circleci-dk

version: 2
jobs:
  build:
    docker:
      - image: circleci/ruby:2.4.1
    steps:
      -checkout
      run: echo "A first hello"

ssh-keygen -t ed25519 -f ~/.ssh/project_key -C dvk1@students.uwf.edu
