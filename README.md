# Deployer son infrastructure avec Ansible et Docker

<div id="top"></div>


<!-- ABOUT THE PROJECT -->
## A propos
C'est un playbook Ansible qui a pour but de configurer la machine distante, y installer Docker, cloner un repo privé et monter les containers associés a ce repo. 

## Stack utilisée
* [Ansible](https://www.terraform.io/) 
* [Docker](https://www.docker.com/)

## Prérequis
* [Terraform](https://www.terraform.io/downloads)
* [Docker](https://docs.docker.com/engine/install/)
* [Python3](https://www.python.org/downloads/)

<!-- ROADMAP -->
## Roadmap

- [x] Configurer le script principal.
- [x] Faire du SOC et créer un role par utilité finale.
- [x] Génrer les clés __SSH__ pour Github directement avec Ansible.

Voir les [issues en cours](https://github.com/jerome-karabenli/ansible_docker_deploy/issues) pour voir la liste complete des fonctionalités proposées et les bugs existants.


<!-- HOW TO -->
## Documentation
Vous trouverez [__un article sur mon blog__](https://jkarabenli.dev/posts/deploy-ansible-docker/) expliquant l'utilisation des fichiers dans ce repo. 

<!-- CONTRIBUTING -->
## Contribuer

Les contributions sont ce qui fait de la communauté open source un endroit incroyable pour apprendre, s'inspirer et créer. Toutes les contributions que vous apportez serront __grandement appréciées__.

Si vous avez une suggestion qui améliorerait le projet, vous pouvez `fork` le repo et créer une `pull request`. Vous pouvez aussi simplement ouvrir une `issue` avec le tag "enhancement".
N'oubliez pas de mettre une étoile au projet ! Merci encore!


1. Fork le projet
2. Créez votre branche (`git checkout -b feature/AmazingFeature`)
3. Commit vos changements (`git commit -m 'Add some AmazingFeature'`)
4. Push sur votre branche (`git push origin feature/AmazingFeature`)
5. Ouvrir une __Pull Request__


<!-- CONTACT -->
## Liens

Lien du blog: [jkarabenli.dev](https://jkarabenli.dev/posts)

Lien du projet: [Github](https://github.com/jerome-karabenli/ansible_docker_deploy)