Sync up files
=============

Asyncly transfer files to a remote server.

For this to work:
* `Sublime`
* `Command on Save` plugin for `Sublime`
* This in `Command on Save` plugin preferences file:
```
{
	"commands": {
		"/WORK_SPACE_DIR_EXAMPLE": [
			"echo \"rsync -avz /WORK_SPACE_DIR_EXAMPLE SERVER_EXAMPLE.com:/home/ \" >> /tmp/cmds"
		]
	}
}
```
