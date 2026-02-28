Linux directory structure
==========================

/         
├── bin
├── boot
├── dev
├── etc
├── home
│   ├── user1
│   ├── user2
│   └── ...
├── lib
├── opt
├── proc
├── root
├── sbin
├── tmp


/ (Root Directory): The top-level directory that contains all other directories.

/bin: Contains essential binary executables (commands) that are required for basic system operation, available for all users (e.g., ls, cp).

/sbin: Contains system binaries, commands that are typically used by the superuser for system maintenance and configuration.


/etc: Houses configuration files for the system and installed applications. This directory is critical for system administration.

/home: Contains home directories for all users. Each user has their own subdirectory here (e.g., /home/user1).


/dev: Contains device files, which represent hardware components (e.g., hard drives, USB devices) as files.


/root: The home directory for the root user (superuser).

/opt: Used for optional software packages that are not part of the standard distribution, often third-party applications.


/lib: Contains shared libraries needed by the binaries in /bin and /sbin. 

/proc: A virtual filesystem that provides information about running processes and system information. Files here are generated dynamically.

/tmp: A directory for temporary files. It is often cleared on reboot.
