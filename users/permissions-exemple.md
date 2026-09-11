# Users and Permissions

## 0bjective

This section documents the Linux user, group, ownership, and permission management exercises performed during this laboratory.

The goal is to understand how access control works on a Linux system and how permissions can be used to protect resources.

## Users Created

The following users were created for the laboratory:

- 'analyst'
- 'engineer'

## Groups Created

The following groups were created:

- 'finops'
- 'cloud'

## Group Membership

The 'analyst' user was added to the 'finops' group.

The 'engineer' user was added to the 'cloud' group.

## Commands Practiced

### User management

'''bash
sudo adduser analyst
sudo adduser engineer
id analyst
id engineer

### Group management

'bash
 
-sudo groupadd finops
-sudo groupadd cloud
-sudo usermod -aG finops analyst
-sudo usermod -aG cloud engineer
-getent group finops
-getent group cloud

### Permissions

'bash

-chmod 644 file
-chmod 600 file
-chmod 750 directory

### Ownership

'bash

-chown user:group file

''' test

