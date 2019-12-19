# Task

The tasks were to specify the version of the mongodb and configure the mongod.conf file so that we replace the default ips
with the new bindip that we wanted to specify, and doing so thorough 3 main steps.

1. specify the synced folder on the host machine that holds the file we want to replace it with and syncs that with the virtual machine path.
2. removes the default mongod.conf file so we can replace it
3. syncing the first location WITHIN the vm with second location WITHIN the vm so the configurations can take effect.


In order to find the database network details we used cat/etc/mongod.conf and copied those to the one on our host machine
which we wanted the virtual machine to synced with and move to another folder within the vm for it to take effect. but first
on the host machine location we changed the bind ip so that the bindip was auto changed in the vm spin up.
