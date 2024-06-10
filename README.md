# Nginx-
How to Install Nginx using Ansible Playbook on Ubuntu VM 

## Qu’est-ce que Nginx ?

Nginx est un serveur Web gratuit et open source. Considérez-le comme un agent de la circulation pour les sites Web, dirigeant les visiteurs vers le bon contenu en ligne rapidement et efficacement. Il est connu pour ses hautes performances, sa stabilité et son évolutivité, ce qui le rend populaire sur les sites Web à fort trafic comme Netflix et Spotify.

## Qu’est-ce qu’Ansible ?

Ansible est comme une partition de chef d'orchestre (playbooks) pour orchestrer des tâches dans la salle symphonique (serveurs) . Tout comme la notation précise de la partition garantit l'exécution harmonieuse d'un morceau musical , les playbooks Ansible garantissent une configuration et un déploiement transparents sur votre infrastructure.

### Éléments essentiels:

Ansible : Outil de gestion de configuration pour automatiser les tâches sur des serveurs distants.

Nginx : logiciel de serveur Web chargé de fournir des pages Web aux utilisateurs.

L'accès SSH sans mot de passe et l'élévation des privilèges sont essentiels pour l'exécution d'Ansible.

HTML : Langage utilisé pour structurer et afficher le contenu des pages Web.

YAML : langage de sérialisation de données utilisé pour les playbooks Ansible.

Ansible automatise les tâches sur les serveurs distants à l'aide de playbooks.

Nginx sert des pages Web aux utilisateurs.

## Ansible installed
`Sudo apt update`

`sudo apt upgrade`

`sudo apt install ansible`

![image](https://github.com/JRMARIEM/Nginx-/assets/161127704/1ff52982-c220-480d-9d9c-b7d2750d07c0)


# STEP 1 CREATE ANSIBLE INVENTORY

` vi inventory`

![image](https://github.com/JRMARIEM/Nginx-/assets/161127704/4050461c-9e3b-4536-a26a-91487b0850d1)

* PING ALL THE HOSTS


![image](https://github.com/JRMARIEM/Nginx-/assets/161127704/b47cb9cd-9016-4233-877f-76a0e10cc544)

# STEP 2 : CREATE ANSIBLE PLAYBOOK

Create nginx-playbook.yml playbook defining tasks:

`vi inginx.yml`

# Run Ansible Playbook

![image](https://github.com/JRMARIEM/Nginx-/assets/161127704/d4a820d6-b01f-4d47-8466-c9ba0bc92112)

![image](https://github.com/JRMARIEM/Nginx-/assets/161127704/d38f2a48-8ac7-4aa4-8410-96aeaa8c5285)

# TEST
NOW Goto web browser and type in localhost/hello-world/

![image](https://github.com/JRMARIEM/Nginx-/assets/161127704/a5942c7b-9b06-427b-be51-7f427956e540)







