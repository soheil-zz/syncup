Sync up files
=============

Asyncly transfer files to a remote server.

For this to work:
* Run `./syncup`
* Use `Sublime`
* Install `Command on Save` plugin for `Sublime`
* Put this in `Command on Save` plugin preferences file:
```
{
	"commands": {
		"/WORK_SPACE_DIR_EXAMPLE": [
			"echo \"rsync -avz /WORK_SPACE_DIR_EXAMPLE SERVER_EXAMPLE.com:/home/ \" >> /tmp/cmds"
		]
	}
}
```


![Sync up Notification](notification.png)