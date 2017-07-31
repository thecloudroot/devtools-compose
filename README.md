# Open source development environement with docker-compose

A self-deployable, directly usable docker-compose of the following containers:

* Jenkins
* Mattermost
* ownCloud
* PostgreSQL
* GitLab

Clone the repo, start through the script and you'll get all the services from above accessible through `[service].[hostlocalip]`.


## Setup

```
git clone https://github.com/Ivaprag/devops-compose.git
cd devops-compose
# You might put sudo before launching the script, depending on your docker user group.
./init.lsb.sh start
```

Wait until the magic is done and here you go, you didn't even have to touch your DNS services. 

For example: `jenkins.192.168.1.2` to access to your Jenkins.


## Backup and Restore

It may be best to backup and restore volumes under `/var/lib/docker/volumes`.


## Contribution

This is an open source software licensed under Apache-2.0.
Feel free to open issues or pull requests.
