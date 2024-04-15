# Remote Github Setup with SSH


## Creating SSH Key's

You need to have SSH key's created in order to authenticate when
doing any activity in connecting to Github.  You will need to use the
command `ssh-keygen` to do so, but I won't detail the specifics here.



## Testing Connection w/ SSH Key

```bash
ssh -T git@github.com
```

As long as you have the public key imported to the Github site, you
should get something like the following message:

```bash
> Hi USERNAME! You've successfully authenticated, but GitHub does not
> provide shell access.
```


