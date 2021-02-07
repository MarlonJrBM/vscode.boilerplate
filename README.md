# vscode.boilerplate

Boilerplate for simple C++ projects in vscode. Main features are:
  - Makefile
  - VsCode files (to automatically compile, run, debug, etc)
  - Clang-Format file (coding guidelines plz)

Remember to modify information in Makefile and .vscode/launch.json with files particular to the project in question.

*Note to future self: if you don't like what's in the above files, they're not set in stone: modify them !*

## How to put this in source control

*Because yes, I forget it all the time*
```bash
git init
# Copy boilerplate and write some files
git add # insert all your files here
git commit
```

This creates a local repository, now to connect it to github:

Create github reposity in github.com and then:

```bash
git remote add origin #insert git URL here
git push -u origin master
```
