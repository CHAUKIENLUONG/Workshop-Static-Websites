+++
title = "GitHub Actions Workflow"
date = 2025
weight = 1
chapter = false
pre = "<b>4.1. </b>"
+++

Create a file named .github/workflows/deploytoS3.yml in your repository:

        name: Upload Website
        on:
        push:
            branches:
            - main
        jobs:
        deploy:
            runs-on: ubuntu-latest
            steps:
            - uses: actions/checkout@v3
            
            - name: Configure AWS credentials
            uses: aws-actions/configure-aws-credentials@v2
            with:
                aws-access-key-id: ${{ secrets.AWS_ACCESS_KEY_ID }}
                aws-secret-access-key: ${{ secrets.AWS_SECRET_ACCESS_KEY }}
                aws-region: us-east-1
            
            - name: Deploy to S3
            run: |
                aws s3 sync website/ s3://${{ secrets.AWS_S3_BUCKET }} --acl public-read --follow-symlinks --delete

* **branches:** [your branch]

* With **aws-region:** your designated region

* **aws s3 sync website** — where is the folder containing the .html files.

