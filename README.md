# SecPass Manager
A simple password manager that use in built 'pass' command and gpg keys for encryption

### SDG 9: Industry, Innovation and Infrastructure

## Introduction
SecPass is a simple password management tool that utilizes the linux pass command tool to store passwords inside gpg encrypted files inside a directory 
residing at ~/.password-store. The pass utility uses a series of commands to store passwords, add or delete, edit, generate, synchronze and manipulate 
passwords securely.
In this digital age and being tech women, we use our devices for various activities and we need to keep our eye on security. 
That is storing strong passwords, and files in safe locations. Fortunately, for every usage there are tools and thus as a group we 
created the SecPass as a training project, in hopes of learning how commercial tools like LastPass and Keepass work without putting our
data at risk or spending limited resources.

### Benefits of SecPass

* pass is open source and thus a user can update the application, and the linux community is always identifying bugs and coming up with extensions 
making more desirable than other applicayions.
* One needs not to make any purchase as the pass command in a linux command tool.
* The password.store can remain in your system only, or you can sync it with a private git repository.
* It is encrypted with GnuPG to a level of your choosing
* The pass command is well documented in the man page thus simple to use and debug.
* It is a command line based application but there are GUI extensions available.

## Technologies used
*Project is created with:*
 1. A linux distribution Operating System
 2. A laptop that runs BSD, MacOS Xor any UNIX-derivatives
 3. Workflow tools:
    1. _**pass**_ -provides the centre for the password store and the access to it.
    2. **GnuPG** - offers the tools for encrypting the password store
    3. **dmenu** - it lists the available passwords
    4. **git** - a version control system for software projects which allows access from different locations and restoring old versions.
  
  ## Setup
  Initializing the password store 
  ` ` `
  pass init "sally.mukami@womentechsters.org"
  ` ` `


