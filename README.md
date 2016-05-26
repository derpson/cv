CV Template
===========

**[Web Version](http://derpson.github.io/cv/)**

Hacking
-------

Content edits should be made to the `cv.md` file. The idea is that all content
will be changed here, and we use pandoc to transform the markdown CV betwen
formats.

Requirements (docker, pandoc):

	brew install pandoc
	brew install docker
	brew cask install virtualbox
	brew install boot2docker
	launchctl load ~/Library/LaunchAgents/homebrew.mxcl.boot2docker.plist
	ln -sfv /usr/local/opt/boot2docker/*.plist ~/Library/LaunchAgents
	eval "$(boot2docker shellinit)"

Usage:

	make pdf html
