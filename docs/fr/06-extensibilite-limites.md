# 6. Extensibilité et limites

Alloy est conçu par couches : primitives, réseau, providers, signers, contrats, transports et utilitaires. Un projet peut sélectionner uniquement les crates nécessaires et remplacer une couche adaptée à son environnement.

Les types de réseau et les traits rendent possibles des intégrations Ethereum, Optimism et d’autres chaînes compatibles, à condition de modéliser correctement leurs règles.

La bibliothèque ne connaît pas la vérité économique d’une application. Elle encode des messages et expose des réponses du nœud ; l’application reste responsable des contrôles de slippage, des permissions, des confirmations et de la gestion des clés.

Périmètre : ce parcours traduit l’organisation des primitives, providers, réseaux, transactions et macros de contrats du dépôt. Aucune installation, compilation ou exécution de test n’a été effectuée. Consulter les suites officielles pour une validation concrète.

Retour : [sommaire du parcours](README.md).
