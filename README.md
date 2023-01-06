# 2023-01-06_sample-terraform

## Prerequisites
Install tools.
```sh
$ brew install tfenv
$ brew install awscli
```

Install specific version of terraform and use it.
```sh
$ tfenv install 1.3.7
$ tfenv use 1.3.7
```

Configure AWS IAM credentials.
```sh
$ export AWS_ACCESS_KEY_ID=[YOUR_AWS_ACCESS_KEY_ID]
$ export AWS_SECRET_ACCESS_KEY=[YOUR_AWS_SECRET_ACCESS_KEY]
```

## Installation
```sh
$ git clone git@github.com:kkznch/2023-01-06_sample-terraform.git
```

## Usage
Initialize terraform only one time.
```sh
$ terraform init
```

Reflect terraform code to infrastructure.
```sh
$ terraform apply
```

Discord all terraform content reflected in infrastructure.
```sh
$ terraform destroy
```
