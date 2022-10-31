# ansible create a Nomad server
You could have 2 type of Nomad server : 
* Leader
* Follower
You terraform install you will install either one or other  
* by declaring an environement variable 
```
TF_VAR_NOMAD_SERVER_LEADER=true terraform apply --auto-approve
```
* by declaring 
```
NOMAD_SERVER_LEADER: true 
```
in the `vars/main.yml` file.
