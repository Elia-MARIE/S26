# Sécurité des applications - 17/03/25
## Méthodes de sécurisation des applications
THOMAS MICHEL
<br>
#### Introduction
La formation des utilisateurs et savoir être et diplomatie sont des notions à prendre en compte.
Formation + mise en place d'aides pour éviter les mauvaises pratiques.
La réalisation d'audits réguliers doit être gérer avec toutes les parties prenantes.<br>
*NB* : Les Wifi sont très vulnérables.

#### I - Questions juridiques

##### ISO 27001
Définit les méthodologies pour identifier les cyber-menaces, maitriser les risques associés etc.

##### RGPD
cf ressources de la CNIL

#### II - Les actions à mettre en place
Il existe un site qui permet d'évaluer les types de risque.
Les vunérabilités peuvent avoir de nombreuses origines : composants, outils, logiciels, code source, etc.
Vigilance vague de phishing.
Double authentification, application SSO (typiquement GeOrchestra), LDAP, OAuth.
Panne matérielle ou origine humaine.

#### III - Méthodes d'ingénierie sociale
Précautions et règles d'hygiène.
- Avertir : formation/pédagogie
- Usurpation/corruption
- Incendie
Cryptohgraphie

#### IV - Proxy
DMZ, pare-feu

#### V - Qualité du code
CICD

#### VI - Sauvegardes
- sauvegarde complète
- // différentielle
- // incrémentielle/incrémentale
pgDump -> script pour sauvegarde mais il faut pas que ça tombe en panne sinon il faut trouver quelque chose qui fonctionne quand même.
Dans ce cas, on utilise un système de réplication (2 machines).
Pour automatiser, on utilise un crontab (https://www.linuxtricks.fr/wiki/cron-et-crontab-le-planificateur-de-taches)
Dans chaque application, il y a un fichier log à lire !
