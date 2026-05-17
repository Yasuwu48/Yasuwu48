## Hi there 👋
name: Update README

on:
  schedule:
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    name: Update Profile README
