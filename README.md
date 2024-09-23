Role Ansible: Conteneurisation d'apache
=========

## Objectif
Nous allons créer un rôle Ansible pour déployer un serveur Apache conteneurisé.

La structure du rôle est la suivante :

![alt text](images/image.png)

## Test du role
Voici notre playbook de test :

![alt text](images/image-3.png)

## Déploiement

Pour déployer le serveur Apache conteneurisé, exécutez le playbook apache.yml à l'aide de la commande suivante:

```bash
ansible-playbool apache.yml
```
Client1

![alt text](images/image-1.png)

Client2

![alt text](images/image-4.png)

## Test du déploiement

Ouverture des ports :

Sur l'environnement eazylab, ouvrez le port 80 :

Depuis client1 pour l'environnement de production.

![alt text](images/image-2.png)

Depuis client2 pour l'environnement de staging.

![alt text](images/image-5.png)


## Conclusion

Ce mini-projet Ansible a permis d'explorer plusieurs concepts clés liés à l'automatisation de la configuration et du déploiement, notamment la création d'un rôle pour le déploiement d'un serveur Apache conteneurisé. À travers ce projet, j'ai acquis une meilleure compréhension de la gestion des rôles Ansible, de la configuration des services en conteneur, ainsi que de l'utilisation des playbooks pour orchestrer ces déploiements.
