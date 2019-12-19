The tasks were to specify the version of the mongodb and configure the mongod.conf file so that we replace the default ips
with the new bindip that we wanted to specify, and doing so thorough 3 main steps.

1. specify the synced folder on the host machine that holds the file we want to replace it with and syncs that with the virtual machine path.
2. removes the default mongod.conf file so we can replace it
3. syncing the first location WITHIN the vm with second location WITHIN the vm so the configurations can take effect. 
