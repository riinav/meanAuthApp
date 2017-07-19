
## Linux mongodb service

Start mongodb <br/>
`$ systemctl start mongodb.service`

Stop mongodb immediately <br/>
`$ systemctl stop mongodb.service`

Restart mongodb <br/>
`$ systemctl restart mongodb.service`

Show the status of a mongodb, including whether it is running or not <br/>
`$ systemctl status mongodb.service`

Check whether mongodb is already enabled or not <br/>
`$ systemctl is-enabled mongodb.service`

Enable mongodb to be started on bootup <br/>
`$ systemctl enable mongodb.service`

Disable mongodb to not start during bootup <br/>
`$ systemctl disable mongodb.service`
