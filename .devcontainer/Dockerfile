FROM php:8.2.10
RUN apt update &&\
    apt install git &&\
    chmod +x .devcontainer/install-composer.sh && ./.devcontainer/install-composer.sh &&\
    sudo mv composer.phar /usr/local/bin/composer
