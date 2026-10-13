# Zéphyr — L’Essentiel 🌸

**FR · Prototype personnel d'affichage e-paper, conçu et expérimenté avec ChatGPT et Codex.**  
**EN · Personal e-paper information display prototype, designed and explored with ChatGPT and Codex.**

> **Statut / Status:** Prototype en développement · Work in progress  
> **Ce dépôt / This repository:** Démonstration de format JSON, pas l'application complète · JSON format demonstration, not the complete application.

## 🇫🇷 Le concept

Une interface minimaliste, destinée à un petit écran e-paper vertical : **trois informations vraiment utiles**, sélectionnées et hiérarchisées pour la journée.

L'objectif n'est pas d'afficher le maximum de données, mais de montrer **la bonne information au bon moment**, avec une consommation et une complexité maîtrisées.

Le projet explore :
- La priorisation d'informations issues de différentes sources (agenda, météo, messages et autres signaux utiles).
- Un format de données simple et autonome pouvant être affiché sur un petit écran.
- Le cache, le fonctionnement local et le comportement en cas d'indisponibilité d'une source.
- La personnalisation et un ton d'assistant reconnaissable, sans surcharger l'affichage.

### Contenu de ce dépôt

- [`essentiel.json`](./essentiel.json) : **exemple de démonstration** de trois informations hiérarchisées avec date, contexte et signature.

Le code de la passerelle locale, les intégrations privées et le dispositif matériel ne sont **pas publiés ici**. Ce dépôt ne prétend donc pas proposer une application prête à installer.

## 🇬🇧 About the project

**Zéphyr — L’Essentiel** explores a small portrait e-paper display that shows **three carefully prioritized daily items**, rather than an endless dashboard.

The broader experiment involves relevant daily information, local-first processing, graceful offline behavior, lightweight data exchange and a calm reading experience.

### What is available here?

- [`essentiel.json`](./essentiel.json): a **sample demonstration payload** showing the structure of three prioritized items, a date, context and an optional signature.

The complete local application, private integrations and hardware implementation are **not published in this repository**.

## 🧭 Méthode / Process

`Idée → contraintes → spécifications → Codex → essais → corrections → itérations`

Ce projet fait partie de mon exploration de la création assistée par IA en tant que **créateur non développeur de métier**.

This is part of my hands-on exploration of AI-assisted building **without being a professional software developer**.

---

**Eric / Terrelfe** · [GitHub profile](https://github.com/magerericsev-design)  
*Projet personnel indépendant — aucune affiliation avec OpenAI.*
