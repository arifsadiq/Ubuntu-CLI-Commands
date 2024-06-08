# I) User Management
w : shows which users are logged in

who : Displays information about the user who are currently logged in

sudo adduser [username] : Creates a new user

sudo deluser [username] : Deletes a user

sudo passwd [username] : Sets or changes the password of a user

su [username] : Switches user

sudo passwd -l [username] : Locks a user account

sudo passwd -u [username] : Unlocks a user account

sudo chage -l [username] : Check password expiration settings

sudo chage -M [DAYS] [username] : Set password expiration for a user

# II) Group Management
id [username] : Displays user and group IDs

groups [username] : Shows the groups a user belongs to

sudo addgroup [groupname] : Creates a new group

sudo delgroup [groupname] : Deletes a group
