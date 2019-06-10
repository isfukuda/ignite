## ignite image import

Import a VM base image

### Synopsis


Import a new base image for VMs. This command takes in an existing ext4 block
device file. Used in conjunction with "export" (not yet implemented).


```
ignite image import <path> [flags]
```

### Options

```
  -h, --help                   help for import
  -k, --import-kernel string   Import a new kernel from /boot/vmlinux in the image with the specified name
  -n, --name string            Specify the name
```

### Options inherited from parent commands

```
  -q, --quiet   The quiet mode allows for machine-parsable output, by printing only IDs
```

### SEE ALSO

* [ignite image](ignite_image.md)	 - Manage VM base images

###### Auto generated by spf13/cobra on 10-Jun-2019