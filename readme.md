## Building packer images

```packer validate aws-ami.json```

#### Enter your own AWS access key and secret access key

```packer build -var \ 'aws_access_key=' -var \ 'aws_secret_key=' aws-ami.json```