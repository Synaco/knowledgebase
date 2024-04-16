# Timedatectl

You can use the `timedatectl` command to update the server to be your
time zone versus the default UTC time.

To list the available timezone formats you can run:

```bash
timedatectl list-timezones
```

Then based on what your timezone is you can run the following command:

```bash
sudo timedatectl set-timezone America/New_York
```

**NOTE:** It seems that in enterprise environments the servers are left
to run on UTC time or unix time stamp for consistency. If there is a 
need to see the time in your timezone, you would do so externally
from outside the server.  For example, for logs, you would ingest them
into a program that would translate the time for you.



## Resources

* [Timedatctl command][1]  
* [Computerphile: The Problem with Time & TimeZones][2]  
* [Reddit: Should all servers timezone be UTC?][3]  


[1]: https://linuxize.com/post/how-to-set-or-change-timezone-in-linux/
[2]: https://www.youtube.com/watch?v=-5wpm-gesOY&ab_channel=Computerphile
[3]: https://www.reddit.com/r/linuxadmin/comments/18rl5rs/should_all_servers_timezone_be_utc/
 
