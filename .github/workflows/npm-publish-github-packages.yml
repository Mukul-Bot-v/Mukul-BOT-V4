name: Imran Bot

on:
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  run-bot:
    runs-on: ubuntu-latest

    steps:
      - name: Checkout Code
        uses: actions/checkout@v4

      - name: Setup Node.js
        uses: actions/setup-node@v4
        with:
          node-version: "20"

      - name: Install Packages
        run: npm install

      - name: Start Bot
        run: npm start
