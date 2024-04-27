---
marp: true
class:
  - invert  
---
# Intro: GIT and Unity
***
## Getting Started
***
1. install git: https://git-scm.com/downloads
	- Windows: keep default settings, except: text editor
***
2. get GIT client
	- [Sourcetree](https://www.sourcetreeapp.com/)
	- [Fork](https://git-fork.com/)
	- [GitHub Desktop](https://desktop.github.com/)
	- [Git for Unity](https://github.com/spoiledcat/git-for-unity)
***
3. setup Unity Project Settings (default)
	- Version Control / Mode = Visible Meta Files 
	- Editor / Asset Serialization Mode = Force Text
***
4. `.gitignore`
	- https://raw.githubusercontent.com/github/gitignore/master/Unity.gitignore
	- https://raw.githubusercontent.com/github/gitignore/main/Global/Windows.gitignore
	- Library/
	- Logs/
	- UserSettings/
	- Build/
	- Tmp/
***
5. `git init`
***
6. GIT LFS
	- `git lfs install`
	- `.gitattributes`
	- `*.FILETYPE filter=lfs diff=lfs merge=lfs -text`
	- https://gist.githubusercontent.com/nemotoo/b8a1c3a0f1225bb9231979f389fd4f3f/raw/dc3e8cab80fc62d1c60db70c761b1ffa636aa796/.gitattributes
***
7. GIT remote server
	1. account, authetification, ssh keys
    2. add origin
	3. push
***
8. (clone a copy)
***
## Golden Rules
1. PULL first
2. commit little, commit often
3. precise and conscious commits
	- Unity scenes, prefabs, project settings
4. precise and conscious editing (and saving) in Unity
5. keep commit messages clean
	- use ticket / issue numbers
