#pyenv
Usage:
- After installed, to use virtualenv of specific python version, you need to download the version first to use as a dependency (this does not replace system python):
	- $ pyenv install 3.10.15
		- Where 3.10.15 is the python version you require;
	- $ pyenv virtualenv 3.10.15 alias-of-virtualenv
		- Where 3.10.15 is the version of python on the to be created virtualenv, while alias-of-virtualenv is the associated name that will be called to access the created virtualenv;
	- $ pyenv local alias-of-virtualenv
		- Call this to associate the current directory to the alias-of-virtualenv virtualenv. This needs to be done only once and everytime you access the directory it will remember and activate the virtualenv automatically;