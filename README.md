# ami-coreos
CoreOS image for AWS

## Building

```bash
$ packer build \
  -var "aws_access_key=${AWS_ACCESS_KEY}" \
  -var "aws_access_key=${AWS_ACCESS_KEY}" \
  coreos.json
```
