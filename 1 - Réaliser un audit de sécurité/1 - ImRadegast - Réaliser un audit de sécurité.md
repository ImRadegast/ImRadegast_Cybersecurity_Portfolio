# Évaluation des Contrôles et de la Conformité – Étude de Cas
> Cette étude de cas repose sur une entreprise fictive :

Botium Toys est une petite entreprise américaine spécialisée dans le développement et la vente de jouets. Elle dispose d’un unique site physique qui fait office de siège social, de boutique et d’entrepôt pour ses produits. Toutefois, la présence en ligne de Botium Toys s’est considérablement développée, attirant des clients aux États-Unis ainsi qu’à l’international. Cette expansion exerce une pression croissante sur le département informatique, qui doit désormais répondre aux besoins d’un marché mondial.

Face à cette situation, la responsable du service informatique a décidé de lancer un audit informatique interne. Elle s’inquiète de l’absence d’un plan d’action structuré pour garantir la continuité d’activité et assurer la conformité réglementaire dans un contexte de croissance. Selon elle, un audit interne permettrait de renforcer la sécurité de l’infrastructure de l’entreprise, et d’identifier et atténuer les risques, menaces ou vulnérabilités affectant les actifs critiques.

La responsable souhaite également s’assurer que l’entreprise respecte les réglementations applicables au traitement interne des paiements en ligne, ainsi que celles liées à ses activités dans l’Union européenne (UE).

Elle entame donc la démarche en adoptant le Cadre de cybersécurité du NIST (NIST CSF). Elle définit le périmètre et les objectifs de l’audit, dresse la liste des actifs gérés par le département informatique et réalise une évaluation des risques. L’objectif de cet audit est de fournir une vue d’ensemble des risques encourus ou des sanctions potentielles que l’entreprise pourrait subir du fait de son niveau actuel de sécurité.

# Scénario
>Botium Toys : Portée, Objectifs et  Evaluation des risks

### **Portée de l’audit**

La portée de cet audit est définie comme l’ensemble du **programme de sécurité** de **Botium Toys**.  
Cela inclut :

- Les **actifs** de l’entreprise (équipements et dispositifs des employés),
- Le **réseau interne**,
- Les **systèmes informatiques**.

L’objectif est d’examiner les actifs de Botium Toys ainsi que les **contrôles** et **pratiques de conformité** actuellement en place.

### **Objectifs de l’audit**

- Évaluer les **actifs existants**,
- Compléter la **checklist des contrôles et de la conformité**,
- Identifier les **contrôles** et **bonnes pratiques de sécurité** à mettre en œuvre,
- **Améliorer la posture de sécurité** globale de Botium Toys.

### **Actifs actuels**

Les actifs gérés par le département informatique incluent :

- Équipements sur site pour les besoins professionnels en présentiel
- Équipements des employés : dispositifs utilisateur (ordinateurs de bureau/portables, smartphones), postes de travail à distance, casques, câbles, claviers, souris, stations d’accueil, caméras de surveillance, etc.
- Produits en vitrine disponibles à la vente en magasin et en ligne, stockés dans l’entrepôt attenant de l’entreprise
- Gestion des systèmes, logiciels et services : comptabilité, télécommunication, bases de données, sécurité, commerce électronique et gestion des stocks
- Accès Internet
- Réseau interne
- Rétention et stockage des données
- Maintenance des systèmes hérités : systèmes en fin de vie nécessitant une surveillance humaine


### **Évaluation des risques**

#### Description du risque

Actuellement, la gestion des actifs est insuffisante. De plus, **Botium Toys ne dispose pas de tous les contrôles nécessaires** et **n'est peut-être pas en conformité** avec les réglementations et normes américaines et internationales.


#### Bonnes pratiques de contrôle

La première des cinq fonctions du **NIST Cybersecurity Framework (CSF)** est **Identify (Identifier)**. Botium Toys devra allouer des ressources pour :

- Identifier ses actifs,
- Les classifier,
- Déterminer l’impact potentiel de leur perte, y compris celle des systèmes, sur la continuité des activités.



#### Score de risque

**Score : 8 sur 10**, ce qui représente un niveau de risque **assez élevé**.  
Ce score est attribué à cause du **manque de contrôles** et de **non-conformité aux bonnes pratiques de sécurité**.



#### Commentaires supplémentaires

- L’impact potentiel lié à la perte d’un actif est évalué comme **moyen**, car le département informatique **ne connaît pas précisément quels actifs sont à risque**.
- Le **risque de perte d’actifs** ou de **sanctions réglementaires** est **élevé**, car Botium Toys **ne respecte pas entièrement** les meilleures pratiques liées aux **réglementations de conformité** qui visent à **protéger les données sensibles**.


#### Informations complémentaires

En cybersécurité, les **types de contrôles** peuvent être classés en trois catégories :

- **Contrôles administratifs / managériaux**
- **Contrôles techniques**
- **Contrôles physiques / opérationnels**

#### Types de contrôles (pour défendre et protéger les actifs) :

- **Préventif** : empêche l’incident de se produire
- **Correctif** : restaure un actif après un incident
- **Détectif** : identifie si un incident a eu lieu ou est en cours
- **Dissuasion** : décourage les attaques



## Liste de vérification de l’évaluation des contrôles
> Botium Toys applique-t-il actuellement ce contrôle ?

| Contrôle                                          | Oui / Non | Commentaire                                                                                                     |
|---------------------------------------------------|-----------|-----------------------------------------------------------------------------------------------------------------|
| Moindre privilège                                 | Non       | Les employés ont accès aux données des clients. Cela doit être modifié pour réduire le risque de violation.   |
| Plans de reprise après sinistre                   | Non       | Il n’existe actuellement aucun plan de gestion de catastrophe. Sa mise en place est nécessaire.                |
| Politiques de mot de passe                        | Non       | Une politique existe, mais elle est faible et ne respecte pas les normes actuelles de sécurité.               |
| Séparation des tâches                             | Non       | Les contrôles d’accès relatifs au principe du moindre privilège et à la séparation des tâches n’ont pas été mis en œuvre. |
| Pare-feu                                          | Oui       | Le pare-feu est actif avec des règles de sécurité bien définies.                                               |
| Détection d’intrusion (IDS)                       | Non       | Déployer un IDS pour détecter les menaces et intrusions en temps réel.                                        |
| Sauvegardes                                       | Non       | Aucun plan en place. Il faut implémenter des sauvegardes (incrémentielle, complète ou partielle).              |
| Antivirus                                          | Oui       | Le logiciel antivirus est actif et régulièrement surveillé.                                                    |
| Chiffrement                                       | Non       | Le chiffrement protégerait la confidentialité des données sensibles.                                           |
| Serrures                                          | Oui       | Bien que l’équipe IT ne gère pas les locaux, l’organisation possède des serrures suffisantes.                       |
| Vidéosurveillance en circuit fermé (CCTV)         | Oui       | Le système de vidéosurveillance est opérationnel.                                                              |
| Détection/prévention incendie                     | Oui       | L’organisation possède ces dispositifs, mais l’équipe doit les entretenir et établir un plan d’utilisation.|






