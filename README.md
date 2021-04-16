# Docker-kerberos
A docker image that creates a simple Kerberos KDC server. 

# What you get

 - A KDC for your desired realm.
 - The `kadmin/admin` principal with every permission.
 - The `noPermissions` principal with no permissions. Useful for testing applications that use kerberos principals.
 - The function `kadminCommand` which performs kadmin commands using the `kadmin/admin` principal.

## Running
Just run `docker-compose up` on the root directory of this repo.

## How to customize (eg. change the REALM)

 - Change the variables defined in the file `kerberos.env` as necessary.

## License
docker-kerberos is open source and available under the [MIT license](LICENSE).
