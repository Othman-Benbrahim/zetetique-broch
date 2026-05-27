# Zététique — Skill d'analyse critique

> Skill pour Claude basé sur les filtres de la zététique tels que présentés par Henri Broch dans *"Comment déjouer les pièges de l'information"*.

---

## Présentation

Ce skill équipe Claude d'un système d'analyse critique structuré en **42 filtres**, organisés en deux registres complémentaires :

| Registre | Fichier | Description |
|---|---|---|
| **Facettes** (31) | `references/facettes.md` | Principes épistémiques à mobiliser activement |
| **Effets** (11) | `references/effets.md` | Biais rhétoriques et cognitifs à détecter |

Chaque filtre est développé de façon **indépendante et argumentée** à partir du nom du principe — non comme résumé du livre, mais comme construction autonome utilisable directement par Claude lors d'une analyse.

---

## Structure du skill

```
zetetique-broch/
├── SKILL.md               # Orchestrateur principal : workflow, grille rapide, pointeurs
├── README.md              # Ce fichier
└── references/
    ├── facettes.md        # Les 31 Facettes développées (avec table des matières)
    └── effets.md          # Les 11 Effets développés (avec table des matières)
```

---

## Les filtres

### Facettes — ce qu'il faut faire / savoir

| # | Principe |
|---|---|
| F01 | Les anomalies et les mystères ne constituent pas un fondement |
| F02 | Un scénario n'est pas une loi |
| F03 | Quantité n'est pas qualité |
| F04 | Un mot écrit n'est pas auto-validant |
| F05 | L'analogie n'est pas une preuve |
| F06 | L'inexistence de la preuve n'est pas la preuve de l'inexistence |
| F07 | La non-impossibilité n'est pas un argument d'existence |
| F08 | Possible n'est pas toujours possible |
| F09 | Compétitif n'est pas forcément contradictoire |
| F10 | La bonne foi n'est pas un argument |
| F11 | Positionner le curseur vraisemblance |
| F12 | Accorder toute son importance à l'incertitude d'un résultat |
| F13 | Une analyse globale ou statistique est souvent concluante |
| F14 | Se montrer prudent dans l'interprétation |
| F15 | Ne pas oublier l'exposition sélective et la validation subjective |
| F16 | La nature est sûre |
| F17 | La parcimonie est de règle |
| F18 | Le mode de rejet des données est significatif |
| F19 | Une théorie scientifique est testable et réfutable |
| F20 | L'inférence est nécessaire |
| F21 | Une allégation extraordinaire nécessite une preuve plus qu'ordinaire |
| F22 | Le bizarre — l'improbable — est… probable |
| F23 | L'erreur est humaine, la faillibilité permanente ne l'est pas |
| F24 | L'origine de l'information est fondamentale |
| F25 | La compétence réelle de l'informateur est fondamentale |
| F26 | La force d'une croyance peut être immense |
| F27 | L'illusionnisme a un rôle critique important |
| F28 | L'histoire des sciences et des techniques a son utilité |
| F29 | Le contexte est important |
| F30 | L'alternative est féconde |
| F31 | La charge de la preuve appartient à celui qui déclare |

### Effets — ce qu'il faut détecter

| # | Effet |
|---|---|
| E01 | Effet Bof — Égaliser sans raison suffisante |
| E02 | Effet Boule de neige — Accumuler les détails dans un récit de nième main |
| E03 | Effet Escalade — Adhérer au comportement et non aux raisons |
| E04 | Effet Bi-Standard — Modifier les règles en cours de jeu |
| E05 | Effet Petits ruisseaux — Permettre, par de petits oublis, de grandes théories |
| E06 | Effet Bipède — Prendre l'effet pour la cause |
| E07 | Effet Cerceau — Admettre au départ ce que l'on veut prouver |
| E08 | Effet Puits — Faire un discours profond : creux est efficace |
| E09 | Effet Impact — Utiliser le poids des mots, la connotation |
| E10 | Effet Cigogne — Confondre corrélation et causalité |
| E11 | Effet Paillasson — Faire un choix trompeur des mots utilisés |

---

## Déclencheurs

Le skill s'active sur :

- Demandes explicites : "analyse critique", "zététique", "esprit critique", "pensée critique"
- Évaluation de contenu : "est-ce vrai ?", "comment vérifier ?", "c'est scientifique ?"
- Démontage d'argument : "charge de la preuve", "biais", "pseudoscience", "sophisme"
- Soumission d'une affirmation, d'un témoignage, d'une théorie, d'un phénomène à analyser

---

## Installation

Télécharger le dossier `zetetique-broch/` et le placer dans le répertoire de skills de votre instance Claude (chemin selon votre configuration).

---

## Avertissement éditorial

Les développements de chaque filtre dans ce skill sont des constructions **indépendantes et originales** rédigées à partir du seul nom du principe, tel qu'il apparaît dans le sommaire de l'ouvrage d'Henri Broch. Ils ne constituent pas un résumé, une traduction ou une reproduction du contenu du livre. Pour lire les développements originaux d'Henri Broch, se référer à l'ouvrage source.

---

## Licence

MIT — libre d'usage, de modification et de redistribution avec attribution.
