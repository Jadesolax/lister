Do whatever the f*ck you wish with this project. DevOps interns, create your Dockerfile. Install vim and also upgrade and update apt
RUN docker-php-ext-install -j$(nproc) mysqli
RUN apt-get -y upgrade
RUN apt-get -y update
RUN apt-get -y install vim
