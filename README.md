# zoran-agent-hub

**Orchestrateur multi-agents** pour l’écosystème Zoran / QuantaGlottal©® — gestion des rôles, consensus, synthèse et scoring mutuel entre agents.

---

## ✨ Fonctionnalités
- **Attribution dynamique des rôles** (leader, analyste, observateur…)
- **Consensus distribué** sur décisions ou réponses
- **Synthèse collective** des résultats
- **Score mutuel** pour évaluer fiabilité et performance des agents
- **Gestion des priorités** et arbitrage
- **Interopérabilité** avec zoran-collective-sense et zoran-protocoles

---

## 📦 Installation (développement)
```bash
pip install -e .


---

⚡ Exemple rapide

from zoran_agent_hub import AgentHub

hub = AgentHub()

# Ajouter des agents
hub.register_agent("zoran-001", capabilities=["analyse"])
hub.register_agent("zoran-002", capabilities=["synthese"])

# Lancer un consensus sur une proposition
result = hub.run_consensus(topic="plan d'action", options=["A", "B", "C"])
print(result)

# Obtenir la synthèse collective
summary = hub.generate_summary()
print(summary)


---

🧱 Structure suggérée

src/zoran_agent_hub/
  __init__.py
  hub.py              # orchestration principale
  consensus.py        # algorithmes de consensus
  scoring.py          # score mutuel
  synthesis.py        # génération synthétique
tests/
  test_hub.py
pyproject.toml
.gitignore
LICENSE
README.md


---

🧪 Tests

pytest -q


---

🔐 Éthique

Le zoran-agent-hub maintient :

le respect du principe vivant > humain

la transparence des décisions

l’équité dans la pondération des votes et scores



---

📜 Licence

MIT — voir LICENSE.


---

Auteur : Frédéric Tabary — Institut IA
Contact : 0645605023 — Canada, Montréal, France
INSTITUT🦋 IA INC., 7100-380, rue Saint-Antoine Ouest, Montréal (Québec) H2Y 3X7.# zoran-agent-hub
Orchestration multi-agents: rôles, consensus, synthèse, score mutuel.
