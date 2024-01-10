```
🐳 Spécifications projet System design - ELK 🐳

Intégration ELK dans votre architecture micro service existantes 

Intégrer Elasticsearch avec votre backend en ajoutant/remplaçant votre base actuelle dans votre docker-compose file (vous pouvez vous appuyer sur le cours en ligne et les example de compose files)
Intégrer Logstash dans votre projet pour effectuer le traitement et l'agrégation des logs (vous pouvez générer des logs si votre application n’en produit pas assez/pas du tout)
Développer minimum une pipeline Logstash qui collecte, traite et transfère les logs vers Elasticsearch et l'inclure dans le fichier docker-compose.yml
Ajouter le service Metricbeat pour collecter et transférer diverses métriques système et de service vers Elasticsearch et inclure Metricbeat dans le docker-compose.yml
 
Streaming de données avec Logstash

Mettre en place un mécanisme ou un script de streaming de données qui génère et envoie des données à Logstash (vous pouvez vous appuyer sur les examples du cours)
Assurer que vos données real time soient correctement formatées et envoyées à Logstash pour traitement (minimum une custom pipeline avec des données différentes du cours).
 

Tests et validation de pipelines

Créer des scripts de test pour valider le bon fonctionnement de Elastic, Logstash et Metricbeat, ainsi que du script de streaming de données.
S'assurer que l'intégration de ces outils n'introduise aucun problème dans la configuration existante. 
Vous avez a minima des fichiers (bash ou autre) de tests qui : 
test la santée de vos conteneurs
test le bon fonctionnement de votre application (front / back)
test du bon fonctionnement de votre stack ELK 
test automatisés dans votre docker-compose-file (minimum 3) 
Fonctionnalités Applicative 

Implémenter des fonctionnalités de recherche dans le frontend qui exploitent Elasticsearch.
Implémenter la fonctionnalité d’auto-completion de Elasticsearch dans votre front. 
Implementer un système d’authentification (JWT, OAuth, SSO…) 
ex de service auth : https://www.youtube.com/watch?v=hmkF77F9TLw&t=2054s / https://github.com/kantancoding/microservices-python 
Surveillance continue du flux stream 

Intégrer Elasticsearch avec Kibana pour la visualisation de données et la surveillance en temps réel.
Fournir un screen shot dans votre readme a la racine de votre GitHub du tableau de bord Kibana dans le cadre de votre solution de surveillance.
Implementer un dashboard kibana avec vos données en real time  
Implementer une action d’integration continue avec elastic curator tool (cf comme dans le chapitre ELK/monitoring de la doc fournie en cours)
 

Documentation de l'Architecture

Mettre à jour le diagramme d'architecture de votre projet pour inclure Elasticsearch, montrant son rôle et son interaction avec d'autres composants/services que vous détaillerez en description.
Votre README.md à la racine de votre GitHub contient les explications nécessaires pour build et run votre projet ainsi qu’une demo online sans erreur et/ou screen shot. 
 

Suivie continue 🚀

Vous devez envoyer un push GitHub par demi journée (au minimum)
Si vous rencontrer un problème bloquant votre avancement ouvrir une issue GitHub (avec screen shot) et contacter le professeur en message privée en envoyant le lien ```
