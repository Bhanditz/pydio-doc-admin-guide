## cells-ctl user delete

Delete a user from the backend

### Synopsis

Delete a role in backend

*WARNING* Policy checks are not yet implemented for the CLI. 
You might corrupt your existing user and group repository,  
So please use with extra care. Also, remember that login are case sensitive. 

EXAMPLE
=======
$ pydioctl user delete -u 'user'

	

```
cells-ctl user delete [flags]
```

### Options

```
  -h, --help              help for delete
  -u, --username string   Login(s) of the group(s) or user(s) to delete
```

### Options inherited from parent commands

```
      --registry string   Registry used to manage services (default "nats")
```

### SEE ALSO

* [cells-ctl user](cells-ctl-user)	 - Manage users

###### Auto generated by spf13/cobra on 19-Jun-2018
