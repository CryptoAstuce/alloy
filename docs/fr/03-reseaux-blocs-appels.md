# 3. Réseaux, blocs et appels

Alloy décrit les réseaux par des types qui associent règles, types de transactions et paramètres de chaîne. Le choix d’un réseau influence la construction et le décodage des messages.

Les providers lisent le numéro de bloc, les en-têtes, les reçus et les traces selon les capacités du nœud. Les appels de contrat utilisent l’ABI pour encoder les paramètres et décoder le résultat.

Un appel simulé ne modifie pas la chaîne. Une transaction envoyée, elle, dépend du mempool et du producteur de bloc ; la réponse RPC ne constitue pas une preuve de finalité.

Les flux asynchrones permettent de suivre des événements ou des nouveaux blocs, avec une gestion explicite des déconnexions.

Suite : [Transactions et signatures](04-transactions-signatures.md).
