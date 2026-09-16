# 4. Transactions et signatures

Alloy fournit des types pour construire des transactions adaptées au réseau sélectionné. Les champs de gas, nonce, destination, valeur et calldata sont encodés selon le format attendu par l’EVM.

Un signer transforme le message en signature, tandis que le provider prend en charge la préparation, l’envoi et le suivi du hash. Séparer ces responsabilités permet d’utiliser un portefeuille matériel, une clé distante ou un compte local.

Les transactions EIP-1559 et les transactions enveloppées ne partagent pas exactement les mêmes champs. Le type réseau évite de produire un encodage incohérent.

La signature autorise une action précise ; elle ne garantit ni l’intention économique ni la sécurité du contrat appelé.

Suite : [Solidity, ABI et génération](05-solidity-abi-generation.md).
