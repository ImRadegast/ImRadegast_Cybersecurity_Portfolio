# Évaluation des Contrôles et de la Conformité – Étude de Cas
> Cette étude de cas repose sur une entreprise fictive :

Botium Toys est une petite entreprise américaine spécialisée dans le développement et la vente de jouets. Elle dispose d’un unique site physique qui fait office de siège social, de boutique et d’entrepôt pour ses produits. Toutefois, la présence en ligne de Botium Toys s’est considérablement développée, attirant des clients aux États-Unis ainsi qu’à l’international. Cette expansion exerce une pression croissante sur le département informatique, qui doit désormais répondre aux besoins d’un marché mondial.

Face à cette situation, la responsable du service informatique a décidé de lancer un audit informatique interne. Elle s’inquiète de l’absence d’un plan d’action structuré pour garantir la continuité d’activité et assurer la conformité réglementaire dans un contexte de croissance. Selon elle, un audit interne permettrait de renforcer la sécurité de l’infrastructure de l’entreprise, et d’identifier et atténuer les risques, menaces ou vulnérabilités affectant les actifs critiques.

La responsable souhaite également s’assurer que l’entreprise respecte les réglementations applicables au traitement interne des paiements en ligne, ainsi que celles liées à ses activités dans l’Union européenne (UE).

Elle entame donc la démarche en adoptant le Cadre de cybersécurité du NIST (NIST CSF). Elle définit le périmètre et les objectifs de l’audit, dresse la liste des actifs gérés par le département informatique et réalise une évaluation des risques. L’objectif de cet audit est de fournir une vue d’ensemble des risques encourus ou des sanctions potentielles que l’entreprise pourrait subir du fait de son niveau actuel de sécurité.

# Scénario
>Botium Toys : Portée, Objectifs et  Evaluation des risks

## Portée de l’audit

La portée de cet audit est définie comme l’ensemble du **programme de sécurité** de **Botium Toys**.  
Cela inclut :

- Les **actifs** de l’entreprise (équipements et dispositifs des employés),
- Le **réseau interne**,
- Les **systèmes informatiques**.

L’objectif est d’examiner les actifs de Botium Toys ainsi que les **contrôles** et **pratiques de conformité** actuellement en place.

## Objectifs de l’audit

- Évaluer les **actifs existants**,
- Compléter la **checklist des contrôles et de la conformité**,
- Identifier les **contrôles** et **bonnes pratiques de sécurité** à mettre en œuvre,
- **Améliorer la posture de sécurité** globale de Botium Toys.

## ✅ Liste de vérification de l’évaluation des contrôles
> Botium Toys applique-t-il actuellement ce contrôle ?
| Oui / Non | Contrôle | Commentaire                                                                |
|-----------|-----------|---------------------------------------------------------------|
|Non   | Moindre privilège |Les employés ont accès aux données des clients. Cela doit être modifié pour réduire le risque de violation de données. |
|Non   | Plans de reprise après sinistre |Il n’existe actuellement aucun plan de gestion de catastrophe. Sa mise en place est nécessaire pour assurer la continuité des activités.|
|Oui| Politiques de mot de passe |Bien qu'une politique de mot de passe existe, ses exigences sont minimales et ne respectent pas les normes actuelles de complexité. Cela met en danger la gestion des identités.|
|Non   | Séparation des tâches |                                                   |
|Oui   | Pare-feu |Le service informatique dispose d’un pare-feu qui bloque le trafic selon un ensemble de règles de sécurité bien définies.|
|Non   | Détection d’intrusion (IDS) |Déployer un IDS pour détecter les menaces et intrusions en temps réel.|
|Non   | Sauvegardes |Comme pour le plan de reprise, ils ne sont pas préparés en cas de violation. Un plan de sauvegarde (incrémentielle, complète ou partielle) doit être mis en œuvre.|
|Oui   | Antivirus |Le logiciel antivirus est actif et régulièrement surveillé par l’équipe informatique.|
|Non   | Chiffrement |Mettre en œuvre le chiffrement  permettrait de protéger la confidentialité des données.  |
|Oui   | Serrures (bureaux, magasins, entrepôts) | Bien que l’équipe IT ne gère pas les locaux, l’organisation possède des serrures suffisantes. |
|Oui   | Vidéosurveillance en circuit fermé (CCTV) |Le système de vidéosurveillance est opérationnel|
|Oui   | Détection/prévention incendie  |L’organisation possède ces dispositifs, mais l’équipe doit les entretenir et établir un plan d’utilisation.|




