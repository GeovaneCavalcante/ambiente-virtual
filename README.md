# Minecurso introdutório à Web com Python e Django

## Instalação em ambiente Linux
1º Cole no terminal

	cd ~

2º Cole no terminal

	mkdir ~/www ~/env

3º Cole no terminal

	gedit ~/.bashrc

4º Cole no final do arquvivo .bashrc

	export PROJECT_HOME=~/www
	export WORKON_HOME=~/env
	source /usr/local/bin/virtualenvwrapper.sh

5º Cole no terminal Obs: Comando único

	sudo apt-get install -y python-pip python3-pip build-essential git python python3  python-dev python3-dev libsdl2-dev  libsdl2-image-dev  		libsdl2-mixer-dev  libsdl2-ttf-dev libportmidi-dev  libswscale-dev libavformat-dev libavcodec-dev zlib1g-dev ffmpeg

6º Cole no terminal Obs: Multiplus comandos

	sudo pip install --upgrade pip virtualenv setuptools
	sudo pip install virtualenvwrapper
	mkvirtualenv --no-site-packages -p /usr/bin/python3 django
	pip install django
