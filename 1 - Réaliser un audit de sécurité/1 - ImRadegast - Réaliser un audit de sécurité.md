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

| Oui / Non | Contrôle                                          | Commentaire                                                                                                     |
|-----------|---------------------------------------------------|-----------------------------------------------------------------------------------------------------------------|
| Non       | Moindre privilège                                 | Les employés ont accès aux données des clients. Cela doit être modifié pour réduire le risque de violation.   |
| Non       | Plans de reprise après sinistre                   | Il n’existe actuellement aucun plan de gestion de catastrophe. Sa mise en place est nécessaire.                |
| Oui       | Politiques de mot de passe                        | Une politique existe, mais elle est faible et ne respecte pas les normes actuelles de sécurité.               |
| Non       | Séparation des tâches                             |  Les contrôles d’accès relatifs au principe du moindre privilège et à la séparation des tâches n’ont pas été mis en œuvre.|
| Oui       | Pare-feu                                          | Le pare-feu est actif avec des règles de sécurité bien définies.                                               |
| Non       | Détection d’intrusion (IDS)                       | Déployer un IDS pour détecter les menaces et intrusions en temps réel.                                        |
| Non       | Sauvegardes                                       | Aucun plan en place. Il faut implémenter des sauvegardes (incrémentielle, complète ou partielle).              |
| Oui       | Antivirus                                          | Le logiciel antivirus est actif et régulièrement surveillé.                                                    |
| Non       | Chiffrement                                       | Le chiffrement protégerait la confidentialité des données sensibles.                                           |
| Oui       | Serrures            | L'organisation dispose de serrures physiques, bien que l'IT ne les gère pas directement.                       |
| Oui       | Vidéosurveillance en circuit fermé (CCTV)         | Le système de vidéosurveillance est opérationnel.                                                              |
| Oui       | Détection/prévention incendie                     | Les équipements existent mais nécessitent un entretien régulier et un plan d’utilisation.                      |





