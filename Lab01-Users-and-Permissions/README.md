# Lab 01 - Linux Users and Permissions

## Objective

Build a simple Linux company environment to practice user management, groups, ownership, and file permissions.

## Scenario

A small company has two departments:

* HR
* IT

Each department should only access its own folder, while everyone can access a shared folder.

## Implementation

* Changed the hostname
* Created the company directory structure
* Created users
* Created groups
* Added users to their groups
* Configured ownership using `chown`
* Configured permissions using `chmod`
* Tested user access

## Commands Used

-'hostnamectl'
-'mkdir'
-'adduser'
-'groupadd'
- 'usermod'
- 'chmod'
- 'chown'
- 'ls'

## Screenshots

![Hostname](screenshots/hostname.png)
![Permissions](screenshots/permissions.png)
![Groups](screenshots/groups.png)
![Access Test](screenshots/access-test.png)

## Skills Covered

- Linux user management
- Linux group management
- File ownership management
- File permission management
- Directory structure organization
- Access control using groups and permissions
- Basic Linux system administration

## What I Learned

- Managing Linux users and groups
- Configuring file ownership and permissions
- Organizing access using Linux groups
- Verifying user permissions through testing

## Real-World Relevance

User and permission management is a fundamental responsibility of Linux system administrators. Organizations use users, groups, file ownership, and permissions to control access to sensitive data and ensure that employees can only access the resources required for their roles. Understanding these concepts is essential for managing Linux servers securely in enterprise and cloud environments.

## Result

Successfully configured a Linux environment with proper user and group permissions for different departments.
