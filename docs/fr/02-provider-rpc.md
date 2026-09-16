# 2. Provider et transport RPC

Le Provider représente l’accès à un nœud Ethereum. ProviderBuilder assemble un transport, un réseau et des couches optionnelles avant d’établir la connexion RPC.

Le transport peut être HTTP, WebSocket ou une autre implémentation compatible. Les couches peuvent ajouter du cache, des retries, de la journalisation ou une politique de réservation de nonce.

Le provider expose des méthodes de lecture et d’écriture tout en conservant les types du réseau sélectionné. Une erreur de transport, de décodage ou de nœud doit rester distinguable.

La configuration du provider est donc une décision d’architecture, pas seulement une URL.

Suite : [Réseaux, blocs et appels](03-reseaux-blocs-appels.md).
