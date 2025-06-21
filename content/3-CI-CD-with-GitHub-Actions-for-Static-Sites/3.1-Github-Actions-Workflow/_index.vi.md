+++
title = "Quy trình GitHub Actions"
date = 2025
weight = 1
chapter = false
pre = "<b>3.1. </b>"
+++

Tạo một file tên là .github/workflows/deploytoS3.yml trong kho mã của bạn:

        name: Tải lên Website
        on:
        push:
            branches:
            - main
        jobs:
        deploy:
            runs-on: ubuntu-latest
            steps:
            - uses: actions/checkout@v3
            
            - name: Cấu hình thông tin xác thực AWS
            uses: aws-actions/configure-aws-credentials@v2
            with:
                aws-access-key-id: ${{ secrets.AWS_ACCESS_KEY_ID }}
                aws-secret-access-key: ${{ secrets.AWS_SECRET_ACCESS_KEY }}
                aws-region: us-east-1
            
            - name: Triển khai lên S3
            run: |
                aws s3 sync website/ s3://${{ secrets.AWS_S3_BUCKET }} --acl public-read --follow-symlinks --delete

* **branches:** [nhánh của bạn]

* Với **aws-region:** vùng bạn chỉ định

* **aws s3 sync website** — nơi chứa thư mục chứa các file .html.

