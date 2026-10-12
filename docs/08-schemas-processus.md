# 08 — Schémas de processus

Les schémas sont écrits en Mermaid pour être prévisualisables sur GitHub.

## 1. La stratégie de contenu

```mermaid
flowchart TD
    A[Audience et questions] --> B[Recherche et tendance]
    B --> C[Choisir une question précise]
    C --> D[Définir public, promesse et preuve]
    D --> E[Écrire et produire]
    E --> F[Revue factuelle et sécurité]
    F --> G[Publier]
    G --> H[Mesurer les signaux disponibles]
    H --> I{Signal utile ?}
    I -- Oui --> J[Approfondir ou créer une suite]
    I -- Partiel --> K[Changer une variable et retester]
    I -- Non --> L[Documenter et changer l'angle]
    J --> B
    K --> B
    L --> B
```

## 2. Le parcours d'une idée vers une publication

```mermaid
flowchart LR
    A[Idée] --> B[Brief]
    B --> C[Sources]
    C --> D[Script]
    D --> E[Captures / visuels]
    E --> F[Montage et sous-titres]
    F --> G[Contrôle qualité]
    G --> H{Conforme et exact ?}
    H -- Non --> E
    H -- Oui --> I[Publication]
```

## 3. Architecture de mesure

```mermaid
flowchart TD
    A[TikTok Studio et données disponibles] --> B[Journal par publication]
    B --> C[Comparaison par pilier et format]
    C --> D[Analyse qualitative des commentaires]
    D --> E[Hypothèses de test]
    E --> F[Programme de la semaine suivante]
    F --> A
```

## 4. Funnel organique réaliste

```mermaid
flowchart TD
    A[Découverte d'une vidéo] --> B[Valeur comprise]
    B --> C[Partage / favori / commentaire]
    B --> D[Visite du profil]
    D --> E[Abonnement]
    E --> F[Retour sur d'autres contenus]
    F --> G[Participation à la communauté si disponible]
```

Ce funnel est un modèle éditorial pour comprendre les étapes possibles. Il ne représente ni les événements garantis pour chaque spectateur ni les pondérations de l'algorithme.
