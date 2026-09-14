# M7-B2 — Comparer 3 évolutions architecturales (MediVox)

> **Repo template.** Binôme par affinité technique. « Use this template » →
> `M7-B2-medivox-evolutions-<binome>`. **Pas de code** — conception et arbitrage.
> Restitution orale **mardi M8** (15 min, slides).

## 🧭 Ce que vous produisez

| # | À faire | Fichier |
|---|---|---|
| 1 | 3 schémas Mermaid (convention cohérente) | `schemas/option_{a,b,c}_TEMPLATE.md` |
| 2 | Comparatif 3×4 chiffré | `comparatif_TEMPLATE.md` |
| 3 | Note 3-5 pages + **recommandation UNE** + décision en une phrase | `note_comparaison_TEMPLATE.md` |
| 4 | Slides 10 max (15 min) | `slides_TEMPLATE.md` |

Renommez les `*_TEMPLATE` en versions finales.

## ✅ Réussite (rappel)

- 3 schémas **comparables** (mêmes formes/couleurs).
- Comparatif 3×4 **chiffré** (ordres de grandeur honnêtes, pas « cher »).
- **Fallback strategies** explicitées par option (seuil / abstention / HITL).
- **UNE** recommandation tranchée, argumentée chiffrée.
- **Garde-fou sobriété explicite** : justifiez le choix (ou non) d'une approche
  LLM. *« 5 agents pour prédire un séjour prolongé »* = signal négatif.
- **Option B = hybride** : le LLM extrait des variables des comptes-rendus, le
  modèle ML prédit. Un assistant RAG qui *répond* aux équipes est un autre
  produit — à mentionner à part, pas à comparer au prédicteur.
- **Avant de rendre** : répétition duo chronométrée (15 min) et une ligne
  « décision en une phrase » en tête de note et de slides.
- Slides lisibles à 3 m (≤ 3 bullets/slide). **Journal de bord** tenu.

## 📚 Ressources

Voir [`./ressources/`](./ressources/) — 7 mini-cours (dont fine-tuning ⭐) + `liens_officiels.md`.

## 🖨️ Rendu slides (optionnel)

`npx @marp-team/marp-cli slides.md -o slides.pdf` ou extension VS Code Marp.
