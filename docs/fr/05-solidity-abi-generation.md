# 5. Solidity, ABI et génération

Les macros Solidity d’Alloy génèrent des types Rust à partir d’interfaces de contrats. Elles produisent l’encodage des fonctions, le décodage des retours, les événements et les erreurs.

Le selector d’une fonction et la disposition ABI doivent correspondre exactement au contrat. Un type mal déclaré peut envoyer un calldata valide mais sémantiquement incorrect.

L’intégration avec solc permet d’utiliser les artefacts de compilation pour créer des bindings typés. Les événements décodés peuvent ensuite être consommés par les flux de logs du provider.

Cette génération réduit les conversions manuelles, mais ne remplace pas la vérification de l’adresse, du réseau et des hypothèses métier.

Suite : [Extensibilité et limites](06-extensibilite-limites.md).
