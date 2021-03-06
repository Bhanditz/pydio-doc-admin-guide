## ./cells config versions

List all configurations versions

### Synopsis


This command allows to manage configurations changes history and eventually
revert to a given version.

A version is created at each call to config.Save() inside the application, along with a log message
and the user originating this call.


```
./cells config versions [flags]
```

### Options

```
      --cat string       Print the JSON content of the config for this version
      --diff string      Display a Diff between two versions, either by providing VERSION1:VERSION2 or just VERSION1 (will be compared to previous one)
      --file string      Point to a specific DB file instead of default
  -h, --help             help for versions
      --restore string   Restore configuration to this specific version
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

* [./cells config](./cells-config)	 - Configuration Manager

###### Auto generated by spf13/cobra on 19-Jun-2018
