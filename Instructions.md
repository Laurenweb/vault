Projet : Gestion d'un coffre-fort numérique

Nous souhaitons réaliser un coffre-fort numérique. L'utilisateur peut y déposer des données confidentielles (sous forme de textes ou phrases par exemple : « Mes codes personnels pour la Banque »), mais pour y accéder, il doit avoir en sa possession 3 clés déterminées à l'avance (2 saisies dans des inputs et 1 clé générée automatiquement au clic lors de la soumission du formulaire).
Les 3 clés seront stockées en base de données.

1. **Les pages du projet**

a. Page d'ajout de données
Une page d'ajout de données avec laquelle, grâce à un **formulaire**, le client peut ajouter des données avec les informations suivantes :
• Adresse email du client
• Données confidentielles (dont la saisie doit se faire à l'aide d'un champ « textarea »)
• Clé personnalisée numéro 1
• Clé personnalisée numéro 2
NB : Les clés personnalisées sont des **champs saisissables par le client**.
Les **informations entrées** ne doivent pas être sauvegardées dans les cookies du navigateur mais seront enregistrées en base de données.

Une fois que le client aura cliqué sur le bouton de soumission du formulaire, une troisième clé aléatoire sera générée automatiquement et elle sera affichée au client, avec un message lui demandant de noter cette clé.

Elle sera en effet nécessaire ultérieurement pour consulter les données du coffre-fort.

b. Page de requête
Une page permettant de **récupérer le détail des données** précédemment enregistrées à partir des informations suivantes :
• Adresse email du client
• Clé personnalisée numéro 1
• Clé personnalisée numéro 2
• Clé personnalisée numéro 3

Si ces informations correspondent à une information en base de données, l'ensemble des informations confidentielles doivent s'afficher. Sinon, une page expliquant qu'aucune information n'a été trouvée devra être affichée au client. (Exemple de message d'erreur : Email incorrect etc…)


2. **Contraintes techniques du projet**

Vous avez des contraintes techniques à respecter dans l'implémentation du projet.

* Le model (entité, classe) doit se nommer **Information**
* L'architecture **MVC** doit être **respectée**.
* Le dossier des vues doit s'appeler **templates**
* Le dossier des modèles doit s'appeler **Entity**


3. **Conseils**

Vous ne disposez pas de visuel illustrant les pages, ni d'indications supplémentaires. Il faudra concilier ce que vous avez appris en formation avec la demande ci-dessus et retrouver les mécanismes qui vous intéressent pour les implémenter. Vous ne serez pas notés sur l'aspect visuel du site internet.

N'oubliez pas démarrer votre projet dans le dossier public (cd public) avant de lancer le serveur.
