# PRÉSENTATION DE DOCKER

Dans ce README, nous allons apprendre à installer et utiliser la technologie Docker pour créer un environnement de développement à l'aide d'images et de docker file et exporter ses projets.

<p align="center">
  <img src="./img/docker.jpg" title="Docker logo" width="500" />
</p>

# PRÉREQUIS

Pour ce tutoriel, vous devez être soit sur Windows ou sur une distribution Linux (pas de MacOS malheureusement).
Il faut faudra également un bon terminal : sur Linux pas de soucis, en revanche sur Windows vous pouvez utiliser [Cmder](https://cmder.net/) qui est un super émulateur de terminal.

<p align="center">
  <img src="./img/cmder.png" title="Cmder image" width="800" />
</p>

Docker est une technologie qui se base sur LXC : Linux Container, il est donc recommandé d'avoir quelques notions élémentaires en Linux et en commande bash. Voici un super 
<a href="https://openclassrooms.com/fr/courses/43538-reprenez-le-controle-a-laide-de-linux" target="_blank">
  tutoriel
</a>  pour apprendre rapidement les bases de Linux.


# INSTALLATION 

## LINUX

Commencez par vous rendre dans votre terminal et tapez ces lignes de commandes :

1. Mettre à jour les apt packages

```bash
sudo apt-get update
```

2. Installer docker

```bash
sudo apt install docker.io
```

3. (OPTIONNEL) Lancer Docker au démarrage

```bash
sudo systemctl start docker
```

```bash
sudo systemctl enable docker
```

4. Vous pouvez maintenant utiliser les commandes Docker dans votre terminal

## WINDOWS

Vous avez le choix entre deux méthodes d'utilisation :

* Soit vous préférez un peu d'interfaces graphiques et vous utilisez Docker Desktop

* Soit vous préférez absolument tout faire dans le terminal et vous utilisez Boot2Docker

### 1. DOCKER DESKTOP

1. Installez ![Docker Desktop](https://www.docker.com/products/docker-desktop) afin de pouvoir se connecter facilement et télécharger des images et des docker files sur le Hub de Docker.

image2

2. Lancer Docker Desktop et lancez Cmder, vous pouvez maintenant utiliser les lignes de commande de Docker

### 2. Boot2Docker
 
 1. Installez simplement [Boot2Docker](https://www.ibm.com/developerworks/community/blogs/jfp/entry/running_ipython_notebooks_in_a_docker_container_on_windows?lang=en), l'installation est très bien expliqué sur ce site. 
 
 2. Lancez Cmder et tapez :
 
 ```bash
 Boot2Docker ssh
 ```
Vous pouvez maintenant utiliser les lignes de commande de Docker



