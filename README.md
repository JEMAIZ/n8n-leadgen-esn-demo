# n8n LeadGen ESN Demo – Agent de Prospection & Upsell pour Cabinets de Conseil / ESN

[![n8n](https://img.shields.io/badge/n8n-Workflow-green)](https://n8n.io)
[![Anthropic](https://img.shields.io/badge/Anthropic-Claude-blue)](https://anthropic.com)
[![Status](https://img.shields.io/badge/Status-Demo_Pro-blue)](#)

## 🎯 Objectif

Automatiser la **génération de leads qualifiés** et l'**upsell** pour les cabinets de conseil / ESN, sans recruter de nouveaux commerciaux.

Ce workflow montre comment passer de quelques données sur un prospect à un **email personnalisé prêt à envoyer**, en quelques secondes avec **Claude d'Anthropic**.

---

## 🧩 Cas d'usage business

**Pain point ESN :**

- Pression constante sur le **CA et le taux d'occupation**.
- Commerciaux qui passent des heures à chercher des infos sur les prospects et à rédiger des emails.
- Difficile de prouver un **ROI concret de l'IA** aux dirigeants.

**Ce que fait le workflow :**

1. Récupère un prospect (ou une liste) depuis un fichier / Google Sheets / CRM.
2. Enrichit le prospect (site web, activité, mots-clés, pains probables).
3. Utilise **Claude (Anthropic)** pour :
   - Résumer le contexte du prospect.
   - Proposer un angle de valeur IA/automation adapté.
4. Génère un **email de prospection ultra-personnalisé** prêt à être envoyé.
5. Enregistre tout dans Google Sheets et peut notifier via Slack / Email interne.

---

## 🔧 Stack technique

- **Automation** : n8n
- **LLM** : **Anthropic Claude** (via API)
- **Stockage** : Google Sheets (ou CSV / base interne)
- **Notifications**
