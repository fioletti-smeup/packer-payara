# Build virtual machine for payara

To build a vmware virtual machine based on centos go into directory centos/vmware,
write vars.json file and give the command:

```shell
packer build --force -var-file vars.json template.json
```

In the same directory there is an example var file.