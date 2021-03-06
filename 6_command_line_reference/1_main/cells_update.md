## ./cells update

Check for available updates and apply them

### Synopsis

Without argument, this command will list the available updates for this binary.
To apply the actual update, re-run the command with a --version parameter.


```
./cells update [flags]
```

### Options

```
  -d, --dry-run          If set, this flag will grab the package and save it to the tmp directory instead of replacing current binary
  -h, --help             help for update
  -v, --version string   Pass a version number to apply the upgrade
```

### Options inherited from parent commands

```
      --fork               Used internally by application when forking processes
      --grpc_cert string   Certificates used for communication via grpc
      --grpc_key string    Certificates used for communication via grpc
      --log string         Sets the log level mode (default "info")
      --registry string    Registry used to manage services (default "nats")
```

### SEE ALSO

* [./cells](./cells)	 - Secure File Sharing for business

###### Auto generated by spf13/cobra on 19-Jun-2018
