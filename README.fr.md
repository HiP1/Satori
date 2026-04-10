# Satori

*🇬🇧 [English](README.md) · 🇪🇸 [Español](README.es.md)*

**Des moments de clarté dans la collaboration humain-IA.**

Satori est un concept zen : un éclair soudain de compréhension où le brouillard se dissipe et où l'on voit les choses telles qu'elles sont vraiment. Pas l'éveil permanent. Pas la destination. Un moment de clarté authentique qui change quelque chose en vous, même si le brouillard revient.

C'est ce que cette skill offre. Pas une solution définitive à la manière dont l'IA interagit avec vous, mais de vrais moments de clarté dans chaque conversation. Des moments où l'IA vous dit ce qu'elle pense vraiment au lieu de ce que vous voulez entendre. Où elle dit « je ne suis pas sûre » au lieu d'inventer une réponse confiante. Où elle demande « avez-vous envisagé ceci ? » au lieu d'acquiescer à votre premier réflexe. Où elle met en lumière le présupposé caché dans un argument au lieu de l'adopter invisiblement.

## Ce que fait Satori

Satori est une skill de calibration comportementale pour assistants IA. Elle cible neuf tendances spécifiques et documentées qui dégradent la qualité de l'interaction humain-IA :

- **Flagornerie :** L'IA vous donne raison pour éviter la friction, même quand le désaccord vous serait plus utile.
- **Fabrication confiante :** L'IA a le même ton de certitude pour ce qu'elle sait et ce qu'elle invente.
- **Rétention de confiance :** L'IA ne vous dit pas à quel point elle est réellement sûre des affirmations qui comptent pour vos décisions.
- **Conformité silencieuse :** L'IA oriente ses réponses selon des hypothèses implicites sans vous le dire.
- **Invisibilité idéologique :** L'IA adopte le cadrage idéologique d'un contenu sans le rendre visible, vous faisant absorber des prémisses que vous n'avez pas évaluées.
- **Recrutement par le contenu :** Un contenu persuasif recrute l'IA comme son avocat plutôt que votre analyste.
- **Amplification du raisonnement :** L'IA utilise son raisonnement pour justifier de vous donner raison plutôt que pour évaluer véritablement.
- **Fermeture sous pression de contexte :** Quand les conversations s'allongent, l'IA commence à conclure au lieu de maintenir la profondeur.
- **Infidélité du raisonnement :** L'IA présente un récit propre qui masque l'incertitude réelle et les considérations concurrentes.

Parallèlement, Satori soutient votre développement cognitif pendant la conversation à travers cinq modes d'engagement calibrés : questionnement socratique (quand ça vous aide à penser, pas quand ça vous fait perdre du temps), génération d'options (des alternatives avec de vrais compromis, pas une meilleure réponse accompagnée d'options décoratives), défi constructif (mettre en lumière le point le plus faible de votre raisonnement), soutien direct (quand vous avez besoin d'aide, pas de pédagogie), et fil d'Ariane (suggérer des connexions que vous avez manquées sans révéler la réponse, pour que vous fassiez la découverte vous-même).

L'objectif : **vous accompagner sur le chemin de la meilleure version de vous-même dans la collaboration humain-IA.**

## À qui s'adresse Satori

- Les personnes qui veulent des retours honnêtes, pas un accord confortable
- Les personnes qui prennent des décisions où la qualité du raisonnement de l'IA compte
- Les personnes en travail créatif qui veulent un collaborateur, pas une machine à oui
- Les personnes qui apprennent quelque chose de nouveau et veulent comprendre, pas juste des réponses
- Les personnes qui traversent des situations difficiles et ont besoin de chaleur et d'honnêteté simultanément
- Les personnes qui ont senti quelque chose changer quand la personnalité de leur IA a évolué et veulent comprendre pourquoi

## Ce que Satori n'est pas

Satori est honnête sur ses propres limites.

C'est une intervention au moment de l'inférence. Elle modifie le comportement de l'IA dans la conversation en fournissant des instructions spécifiques. Elle ne peut pas changer l'entraînement sous-jacent de l'IA. Les améliorations comportementales sont réelles mais temporaires : elles existent dans la conversation où Satori est active et se dégradent quand les conversations deviennent très longues.

Une conversation avec Satori dans un monde d'interactions IA standard ne changera peut-être pas définitivement la manière dont vous interagissez avec l'IA. C'est le problème de dosage que la recherche sous-jacente documente. Satori est un échafaudage, pas une solution. La solution à long terme nécessite des changements dans la façon dont les systèmes d'IA sont entraînés. Satori opère dans l'intervalle entre maintenant et alors.

## Comment utiliser

Téléchargez `satori.skill` depuis la page [Releases](../../releases). Satori suit le standard ouvert Agent Skills (format SKILL.md), adopté par Claude, ChatGPT et plus de 30 plateformes IA.

**Note importante :** la skill elle-même est en anglais. C'est ce que le modèle lit. Mais vous pouvez parler à votre IA dans n'importe quelle langue. Les principes de Satori s'appliquent quelle que soit la langue de la conversation.

### Recommandé : Installer comme skill (bureau/web)

Place Satori dans la zone du prompt système où elle maintient son influence tout au long de la conversation.

**Claude :** Paramètres → Capacités → Skills → Téléverser `satori.skill`

**ChatGPT :** Profil → Skills → Nouvelle skill → Téléverser depuis votre ordinateur. Note : en avril 2026, les skills ne sont disponibles que pour les plans Business, Enterprise, Edu, Teachers et Healthcare. Pas encore disponible pour Plus ou Pro. Si vous n'y avez pas accès, utilisez le Custom GPT ci-dessous.

### Versions pré-configurées (aucune installation requise)

**ChatGPT (Custom GPT) :** [Satori sur ChatGPT](https://chatgpt.com/g/g-69d261c29bf48191b05f615c0b1e5367-satori) — fonctionne pour tous les utilisateurs ChatGPT, y compris le niveau gratuit. Sélectionnez le meilleur modèle disponible. Note : les Custom GPT n'accèdent pas à vos mémoires, instructions personnalisées ou conversations précédentes. Chaque session repart de zéro. Si vous souhaitez Satori avec votre mémoire et historique disponibles, déposez le fichier `.skill` directement dans une conversation normale.

**Gemini (Gem) :** [Satori sur Gemini](https://gemini.google.com/gem/1F-2xSYxBXZy7xV2f0ZjAglWFnDNgZcyn?usp=sharing) — sélectionnez Pro pour de meilleurs résultats, ou Thinking en alternative. Fast risque d'être insuffisant pour des interactions de fond. Les conversations Gemini sont également isolées par défaut, avec un contexte inter-sessions limité.

### Outils CLI

Décompressez et copiez le dossier de la skill dans le répertoire skills de votre outil CLI :

**Claude Code :** `~/.claude/skills/satori/`

**Codex CLI :** `~/.codex/skills/satori/`

**Gemini CLI :** `.agents/skills/satori/` (niveau projet) ou équivalent

### Alternative : Déposer dans la conversation (mobile ou toute plateforme)

Si votre application n'a pas d'interface d'installation de skills (y compris les applications mobiles), vous pouvez déposer le fichier directement dans une conversation. Sur Gemini, renommez d'abord le fichier en `.zip`.

Cela fonctionne mais avec un compromis : les instructions se trouvent dans le corps de la conversation plutôt que dans la zone du prompt système, et glissent vers le milieu du contexte au fur et à mesure que la conversation grandit. La résistance à la dégradation de la skill (l'ancre ◇) aide à contrebalancer cela, mais l'installation via l'interface de skills est préférable quand elle est disponible.

### Le marqueur ◇

Vous remarquerez peut-être un petit ◇ à la fin de certaines réponses. Il apparaît quand les principes de la skill façonnent activement la sortie de l'IA. S'il cesse d'apparaître et que vous n'avez rien dit à ce sujet, l'influence de la skill s'estompe peut-être à mesure que la conversation s'allonge. Vous pouvez ré-ancrer en le mentionnant, ou démarrer une nouvelle conversation avec Satori chargée à nouveau.

## Éthique

Satori est conçue pour que vous soyez le seul bénéficiaire de chaque interaction. Aucun tiers ne devrait profiter de la manière dont la skill modifie le comportement de l'IA. Vous pouvez cesser de l'utiliser à tout moment.

## Licence

CC BY 4.0. Voir [LICENSE](LICENSE) pour les détails.

## Auteur

Ivan « HiP » Phan
ORCID : [0009-0003-1095-5855](https://orcid.org/0009-0003-1095-5855)

Développé à partir de la série Confidence Curriculum. La série documente les problèmes. Cette skill est la réponse déployable immédiate.

---

*Le brouillard ne disparaît pas. Mais dans les moments où Satori est active, vous voyez clairement. Ça vaut quelque chose, même si ce n'est pas tout.*
