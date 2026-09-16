# 1. Primitives et types Ethereum

Alloy organise les primitives Ethereum dans des crates spécialisées : adresses, hashes, quantités, chaînes RLP, types de blocs et transactions. Le meta-crate alloy réexporte les composants utiles pour un usage unifié.

Les types forts évitent de confondre une adresse, un hash ou une quantité brute. Les conversions explicites rendent visibles les frontières entre représentation réseau et valeur métier.

Les macros et dérivations réduisent le code répétitif pour les structures sérialisables. Elles doivent toutefois rester compatibles avec les règles d’encodage Ethereum.

Cette base commune alimente les providers, les portefeuilles, les appels de contrats et les outils de test.

Suite : [Provider et transport RPC](02-provider-rpc.md).
