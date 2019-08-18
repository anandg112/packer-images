## Building packer images

```packer validate aws-ami.json```

```packer validate -var 'do_api_token=' multi-cloud-ami.json```

#### Enter your own AWS access key and secret access key

```packer build -var 'aws_access_key=' -var 'aws_secret_key=' aws-ami.json```

```packer build -var 'do_api_token='-var 'aws_access_key=' -var 'aws_secret_key=' multi-cloud-ami.json```