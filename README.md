# AWS-Network-Projet
L’objectifs de ce projet est de mettre en place une architecture réseau cloud robuste, sécurisé et scalable au sein d'AWS.

## L'Architecture du projet
![image](https://github.com/user-attachments/assets/bd51baed-95d3-4764-9c76-8948fa61c597)

## Service AWS utilisés 
 -VPN: pour établir des connexions sécurisées entre les ressources qui se situe dans une même région;
 
 -VPC(cloud privé virtuel): qui représente nos réseaux;
 
 -Pare-feu WAF: pour sécuriser nôtre application Web et filtré qui peut avoir acces à la ressource qui se trouce sur nos instance privées;
 
 -Security Group: permet de filtrer le trafic depuis n'importe qu'elle source vers notre ressource;
 
 -Transit Gateways: pour interconnecter des clouds privés virtuels (VPCs) qui se trouve soit sur le même compte soit sur des comptes diverses;
 
 -Internet Gateways: qui permet la communication entre nos VPC et Internet;
 
 -Table de routage:permet de router le trafic vers les services destinataires.
 
 -Elastic Load Balancing:pour pouvoir avoir accès à nos appli;
 
 -IAM:(AWS Identity and Access Management) qui permet de contrôler en toute sécurité l'accès aux AWS ressources;
 
 -Amazon S3: qui permet de stocker et protéger n'importe quelle quantité de données(c'est la où sera stocker le code source de notre appli);
 
 -Amazon CloudWatch: qui permet de surveiller les différentes métriques de notre applications; 

ASG: pour déploié des applis dans un environnement hautement dispo et sécurisées;(template de l’image pour mettre en place cela)

## Estimation des coûts
 ![image](https://github.com/user-attachments/assets/af4e0d6d-9bb7-4026-9b43-46d0d0863be8)
