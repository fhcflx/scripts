# README #

These are easy scripts to set up new projects in Github, Gitlab, and Bitbucket using a CLI.

### What is this repository for? ###

* Use the scripts to set up new projects remotely in your preferred git server repository from the command line. You need to have an account in your server and know security specs for it.
* Alpha version - 0.2.0
* [Learn Markdown](https://bitbucket.org/tutorials/markdowndemo) - very useful

### How do I get set up? ###

* Bitbucket-i-repo works anywhere after first run. The other scripts must be run from the folder where they are.
* No configuration needed, except initiate git repo in the desired folder

```
#!git

$ git init
```

* No dependencies
* No database configuration
* Tested in macOs and git bash for Windows, however it should work in unix-based systems; not tested for Windows Command or Powershell (sorry)
* Deployment instructions: just put in any folder and run it

### Known issues ###

* Github script will not work after two-factor authentication set up
* Gitlab script has to be modified for each user, once it has my repo and groups intel. You need to edit the code and use your own groups names and ids

### Contribution guidelines ###

* Writing tests
* Code review
* Other guidelines

### Who do I talk to? ###

* @fhcflx
* fhcflx@outlook.com
* twitter: fhcflx