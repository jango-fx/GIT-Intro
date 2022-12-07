# GIT Intro

## Getting Started

1. install git: https://git-scm.com/downloads
	- Windows: alle default settings außer text editor
2. get GIT client
	- Source Tree
	- Fork
	- GitHub Desktop
	- Git for Unity
3. setup Unity Project Settings (default)
	- Version Control / Mode = Visible Meta Files 
	- Editor / Asset Serialization Mode = Force Text
4. `.gitignore`
	- https://raw.githubusercontent.com/github/gitignore/master/Unity.gitignore
	- https://raw.githubusercontent.com/github/gitignore/main/Global/Windows.gitignore
	- Library/
	- Logs/
	- UserSettings/
	- Build/
	- Tmp/
5. `git init`
6. GIT LFS
	- `git lfs install`
	- `.gitattributes`
	- `*.FILETYPE filter=lfs diff=lfs merge=lfs -text`
7. GIT remote server
	1. account, authetification, ssh keys
    2. add origin
	3. push
8. (clone a copy)