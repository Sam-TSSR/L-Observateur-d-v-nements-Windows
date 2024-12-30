# Vue Personnalisée : Surveillance des Événements DNS

Cette vue personnalisée permet de surveiller les événements liés au service DNS dans l’Event Viewer. (DNS-view.xml) 

### Configuration :
- **Niveaux surveillés** : Critique, Erreur, Avertissement, Information.
- **Sources** : DNS-Server-Service, DNS Client Events.
- **ID d’événements** :
  - 2 : Démarrage du serveur DNS.
  - 4 : Arrêt du serveur DNS.
  - 409 : Erreur de résolution de nom.
  - 501-502 : Échec de chargement de zone.
  - 6001-6002 : Problèmes de réplication DNS.
