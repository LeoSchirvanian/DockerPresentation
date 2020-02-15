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
* Soit vous êtes familier avec Linux et alors vous pouvez utiliser Ubuntu on Windows

* Soit vous êtes totalement pro Windows et vous pouvez utiliser Boot2Docker

### 1. UBUNTU ON WINDOWS

* Rendez vous sur le Microsft Store et téléchargez l'application Ubuntu. Cette dernière permet en fait d'utiliser le terminal d'Ubuntu et de lancer des lignes de commande Ubuntu sous Windows.

image1

* Une fois installée, il est temps d'installer ![Docker Desktop](https://www.docker.com/products/docker-desktop) afin de pouvoir se connecter facilement et télécharger des images et des docker files sur le Hub de Docker.

image2

* Une fois ces étapes effectuées, lancez Cmder avec un terminal en bash et allez à la partie Installation Linux et tapez les mêmes lignes de commande dans Cmder.

### 2. Boot2Docker
 
 * Installez simplement [Boot2Docker](https://www.ibm.com/developerworks/community/blogs/jfp/entry/running_ipython_notebooks_in_a_docker_container_on_windows?lang=en), l'installation est très bien expliqué sur ce site. 
 
 * Une fois cela fait vous avez fini, lancez simplement dans votre terminal favori :
 
 ```bash
 Boot2Docker
 ```




