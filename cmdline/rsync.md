# rsync

The best alternative to `scp`.

```
rsync -avP local/location user@destination:/path/on/server

-a Archieve mode, using recursion and preserves everything.
-v Verbose mode, cause you always want more logs.
-P Progress, what's the latest update? well, now you know!
--exclude 'some_private_file.log' never deploy the local logs again.
```
