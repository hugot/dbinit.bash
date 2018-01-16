# dbinit.bash
Create, destroy and populate development databases in a matter of seconds.
For information on how to use this script, please refer to the man page in the 'man' folder of this
repository.

## Dependencies

### Libraries
This script depends on the [basher](https://github.com/basherpm/basher) package manager
to source the libraries it uses. The libraries it includes via basher are:

- [bash-array-utils](https://github.com/redrock9/bash-array-utils)
- [bash-params](https://github.com/redrock9/bash-params)

### Binaries
To use this script, you will need to have a mysql command line client present on your system.
The script has only been tested with the mariadb mysql commnd line client, so using that is recommended.
If you want to develop with a local db, then you should of course also install a mysql server on your system.


## Installation
With [basher](https://github.com/basherpm/basher):
  
`basher install redrock9/dbinit.bash`
