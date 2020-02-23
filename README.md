# Packer for wasilak/amazon-linux-2

run with:

```bash
packer build -var 'vagrant_cloud_token=XXXX' packer.json
```

or


```bash
packer build -var-file=variables.json packer.json
```
