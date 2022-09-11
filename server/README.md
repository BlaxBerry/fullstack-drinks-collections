# Server Side of FullStack Drinks Collections

- [Tech Stacks](#1-tech-stacks)
- [Folders](#2-folders)
- [Development](#3-development)

<br/>

## 1. Tech Stacks

- [Python]()
- [Django]()
- [pdm]()
- ...

<br/>

## 2. Folders

- `app`: Django's main app

...

<br/>

## 3. Development

### Download and Setup

```shell
# 1. download
git clone <THISPROJECT>

# 2. create .venv of pdm and download all dependencies
pdm install
```

If IDE is **Pycharm**, do not forget to run `pdm install` to create `.venv` before set the Python Interpreter.

The information of pdm printed after running `pdm info` in this project should be like:

```shell
PDM version:
  2.1.1
Python Interpreter:
  /Users/<USERNAME>/<PROJECTNAME>/server/.venv/bin/python (3.10)
Project Root:
  /Users/<USERNAME>/<PROJECTNAME>/server
Project Packages:
  None
```

### Git Commit Message

```shell
git commit -m "fix: bugs & errors"
```

- fix: fix something
- style: modify style of somewhere
- feat: add something new
- docs: modify documents
- perf: enhancement performance
- chore: change libraries

<br/>
