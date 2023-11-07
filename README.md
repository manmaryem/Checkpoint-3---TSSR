# Checkpoint-3---TSSR
## Partie 1 : Gestion des utilisateurs

### Question 1.1 : Lister les comptes utilisateurs
Pour lister les comptes utilisateurs, utilisez la commande :
-	$ cat /etc/passwd

![image](https://github.com/manmaryem/Checkpoint-3---TSSR/assets/137881827/ae89cedb-b92e-4308-943b-30170101b929)

### Question 1.2 : Création d'un compte utilisateur
Pour créer un compte utilisateur, utilisez la commande :
```
$ sudo adduser nom_utilisateur
![image](https://github.com/manmaryem/Checkpoint-3---TSSR/assets/137881827/988bf810-d9bd-4ee8-bf08-9882c24a4918)

### Question 1.3 : Recommandations sur le compte wilder
Il est recommandé de limiter l'accès au compte "wilder" et de ne pas lui accorder des privilèges administratifs. mettre en place des règles de mot de passe complexes et de surveillance des connexions pour renforcer la sécurité.
## Partie 2 : Le stockage

### Question 2.1 : Analyse des disques
Pour voir les systèmes de fichiers actuellement montés, utilisez la commande :
```
$ df -h
![image](https://github.com/manmaryem/Checkpoint-3---TSSR/assets/137881827/4bcba380-8c4c-48e0-bb61-0c20fb19deaa)

- Quel type de système de stockage ils utilisent ?
  
Le type de stockage utilisé est le Rad1 Le RAID 1 est une norme qui vise à améliorer la sécurité des données stockées. Le concept repose sur un réseau de deux disques durs ou plus pour stocker les données de manière miroir, c’est-à-dire en double. Ce processus est également connu sous le nom de "miroir"1. Si un disque tombe en panne, l’autre peut continuer à fonctionner. C’est la façon la plus simple de mettre en œuvre une tolérance aux pannes et son coût est relativement faible2.
![image](https://github.com/manmaryem/Checkpoint-3---TSSR/assets/137881827/ce704374-c4f0-46b1-b250-806840894506)

### Question 2.2 : Gestion du RAID

![image](https://github.com/manmaryem/Checkpoint-3---TSSR/assets/137881827/01eb2476-55c5-425b-b6e0-c676a164f9f4)
![image](https://github.com/manmaryem/Checkpoint-3---TSSR/assets/137881827/304629b3-efce-418c-a482-77810f19ee1d)

- Malheureusement après plusieurs tentatives la machine ne fonctionne plus, malgré avoir fait plusieurs installations.






