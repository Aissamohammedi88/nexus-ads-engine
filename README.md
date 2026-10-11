# nexus-ads-engine
NEXUS ADS ENGINE est un serveur publicitaire complet qui gère : 🏢 Comptes (accounts) avec balance et devise 👤 Utilisateurs avec tokens API 📢 Campagnes avec budgets, stratégies d'enchères, réseaux 📁 Groupes d'annonces (ad groups) avec CPC bid 🎨 Annonces (responsive search ads) avec headlines + descriptions
🚀 NEXUS ADS ENGINE v3.4
Full-stack ad server. Own protocol. Own logic. Own schema.
Un moteur publicitaire complet, autonome, en Python pur. Sans dépendance externe, sans cloud, sans permission. Il tourne sur ta machine. Il t'appartient.
Version (https://github.com/Aissamohammedi88) Python (https://python.org/) SQLite (https://sqlite.org/) License
🎯 C'est quoi ?
NEXUS ADS ENGINE est un serveur publicitaire complet qui gère :
🏢 Comptes (accounts) avec balance et devise
👤 Utilisateurs avec tokens API
📢 Campagnes avec budgets, stratégies d'enchères, réseaux
📁 Groupes d'annonces (ad groups) avec CPC bid
🎨 Annonces (responsive search ads) avec headlines + descriptions
🔑 Mots-clés avec match types (exact, phrase, broad) et quality score
🚫 Mots-clés négatifs pour filtrer le trafic
👥 Audiences custom avec membres hashés (SHA-256)
🎯 Ciblage (location, device) avec bid modifiers
📊 Métriques (impressions, clicks, cost, conversions, revenue)
🏆 Enchères (auction system avec second-price)
🖱 Clics avec détection de fraude
💰 Conversions avec attribution multi-touch
📈 Rapports avec CTR, CPC, CPA, ROAS, timeline
Le tout tourne en local, sur le port 8000, avec SQLite + WAL mode + cache + thread pool.
⚡️ Quick Start
# Clone
git clone https://github.com/Aissamohammedi88/nexus-ads-engine.git
cd nexus-ads-engine

# Lance
python3 ads_engine.py

# Le serveur démarre sur http://localhost:8000
# Un token ADMIN est affiché dans le terminal
