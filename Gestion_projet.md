# Gestion de projet - 17/03/25
## Méthodes de recueil et d'analyse des besoins
FRANCK THUILLIER
<br>
### Conception et maintenance d'applications et d'interfaces SIG
Analyser le besoin est fondamental pour rendre le bon service au client. Il existe diffférentes méthodes d'expression du besoin qui dépendent de notre relation et de l'environnement du client.
Ainsi, on adapte sa réponse à l'interlocuteur.
<br> <br>
*Expression de besoin* :
- Appel d'offre : rédiger le cahier des charges avec le cadre de réponse précis et détaillé,
- Cahier des charges interne : rescence l'ensemble des besoins du client (contrat déjà en place ou dans le cadre privé),
- Note d'expression du besoin / Tickets : format plus souple, souvent contrat déjà en place, pour des petites demandes ou évolution de la demande (méthodologie agile).

Il existe deux principales méthodologies de gestion de projet qui s'appliquent selon le type de structure et le type de projet :
- Cycle en V : adapté aux grands projets, très stricte,
- Agile : adapté à des projets peu définis en amont, plus souple.

#### I - Cycle en V

![](https://www.manager-go.com/assets/Uploads/Cycle-V-min.png)
<br>Généralement, il faut rédiger le Cahiers des charges, les Spécifications Techniques (STG et STD), les Spécifications Fonctionnelles (SF) et le Dossier d'Architecture Technique (DAT). Ce processus est très strict et la documentation du code source est obligatoire, on utilise souvent Git.

#### II - Mode Agile

![](Methodologie_gp.png)

C'est un cycle court (sprints de 3/ semaines) et les cycles se succèdent pour aboutir au produit. L'outil est livré petit à petit. On rédige un Backlog (liste itérative des fonctionnalités souhaitées par le client réparties sur chaque sprint). On utilise un panel d'outil : jira, monday, notion, teams, sharepoint. La gestion du code source est très importante, d'où l'utilisation de Git.
L'idée est d'avoir une continuité de service sur le livrable final, l'aspect DevOps intervient souvent dans la méthode Agile, c'est pourquoi on réalise de nombreux tests d'intégration.
<br>
#### III - TP : Analyse d'une note d'expression de besoin.
Groupe de 2/3. Rédaction d'un cahier des charges dont un porotypage IHM (Interface Homme Machine) et l'architecture technique envisagée.
Outil cartographique web permettant la prise de decision sur l'emplacement d'un commerce et l'analyse des commerces déjà existants. L'outil devra posséder plusieurs fonctionnalités :
- données permettant l'analyse du contexte socio-économique du commerce,
- statistique démographiques,
- analyse des contraintes de l'emplacement
