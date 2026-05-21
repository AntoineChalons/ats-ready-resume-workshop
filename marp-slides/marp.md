---
marp: true
theme: gaia
_class: lead
paginate: false
header: Back to Work Léman
backgroundImage: url('https://marp.app/assets/hero-background.svg')
---

# CV & ATS : passer le premier filtre

Comment créer un CV qui sera **lu**

https://github.com/AntoineChalons/ats-ready-resume-workshop

---

<!-- _class: "" -->
<!-- paginate: true -->

## 📋 Agenda

| Étape | Durée |
|---|---|
| 🤖 Comprendre les ATS     | xx min |
| 🧪 Tester son CV actuel   | xx min |
| 🛠️ Créer un CV avec Typst | xx min |
| 🔁 Retester et comparer   | xx min |
| ❓ Questions              | xx min |

---

## 🤖 C'est quoi un ATS ?

**ATS** = **A**pplicant **T**racking **S**ystem

Un logiciel utilisé par les recruteurs pour :

- 📥 **Stocker** les candidatures dans une base de données
- 🔍 **Analyser** automatiquement les CV
- 📊 **Classer** les candidats par pertinence
- 🚫 **Filtrer** ceux qui ne correspondent pas

---

## 📈 Quelques chiffres clés

- **98%** des entreprises du Fortune 500 utilisent un ATS
- **75%** des CV sont rejetés avant d'être vus par un humain
- Un ATS met environ **6 secondes** à scanner un CV

---

## ⚙️ Comment fonctionne un ATS ?

### Étape 1 — Parsing (extraction)
Le logiciel convertit votre PDF/DOCX en texte structuré :
- Nom, prénom, email, téléphone
- Expériences professionnelles
- Formation
- Compétences

> **Problème** : si la mise en forme est complexe, le parser **échoue** et vos données sont perdues ou mélangées.

---

## ⚙️ Comment fonctionne un ATS ?

### Étape 2 — Matching (correspondance)
L'ATS compare votre CV à l'offre d'emploi :
- 🔑 Recherche de **mots-clés** (compétences, outils, diplômes)
- 📐 Vérifie la **structure** (sections standards attendues)
- 📊 Attribue un **score de pertinence**

### Étape 3 — Classement
Les candidats sont triés par score. Seuls les **meilleurs** arrivent devant recruteur.

---

## ❌ Ce qui fait échouer un CV

| ❌ À éviter | ✅ À faire |
|---|---|
| Tableaux et colonnes multiples | Mise en page **simple, une colonne** |
| Images, logos, icônes | Texte uniquement |
| En-têtes/pieds de page pour les infos clés | Infos de contact **dans le corps** |
| Polices exotiques | **Arial, Calibri, Times New Roman** |
| Barres de compétences graphiques | Listes textuelles de compétences |
| Fichier .jpg ou .png | Format **PDF** (ou .docx) |

---

## 📝 Les 7 règles d'or

1. **Une seule colonne** — pas de mise en page fantaisie
2. **Sections standard** : Expérience, Formation, Compétences
3. **Mots-clés de l'offre** — reprendre le vocabulaire exact
4. **Pas d'images** ni de graphiques
5. **Polices classiques** et taille lisible (10-12pt)
6. **Puces simples** (• ou -) avec indentation cohérente
7. **Pas d'en-tête/pied de page** pour les infos importantes

---

## 🔑 L'importance des mots-clés

L'ATS cherche des correspondances **exactes** avec l'offre :

- ❌ « Gestion de projets » ≠ « Project Management »
- ✅ Si l'offre dit « Project Management » → utilisez **exactement** ce terme
- ✅ Incluez aussi l'acronyme : « SEO (Search Engine Optimization) »

### 💡 Astuce
Lisez l'offre d'emploi, surlignez les **compétences et outils** mentionnés, et intégrez-les **naturellement** dans votre CV.

---

<!-- _class: lead -->

# 🧪 Phase 1 : On teste !

Testons ensemble votre CV

---

## 🧪 Tester son CV — Mode d'emploi

### Rendez-vous sur un de ces sites

1. 🌐 **[JobScan](https://app.jobscan.co/dashboard)**
   Partiellement gratuit · Inscription · Analyse d'annonce

2. 🌐 **[enhancv.com/](https://enhancv.com/)**
   Gratuit · Score + recommandations détaillées

3. 🌐 **[mployee.me/resumescan](https://www.mployee.me/resumescan)**
   Gratuit · Analyse sur 40+ critères

### 📌 Notez votre score ! On le comparera à la fin

---

## 🧪 Que regarder dans les résultats ?

- 📊 **Score global** — votre point de départ
- 🔍 **Problèmes de parsing** — l'ATS a-t-il bien lu vos infos ?
- 📝 **Sections manquantes** — manque-t-il une rubrique standard ?
- 🔑 **Mots-clés** — sont-ils suffisants ?
- 🎨 **Mise en forme** — y a-t-il des éléments problématiques ?

> Notez ce score, on va maintenant créer un CV optimisé ! 🚀

---

<!-- _class: lead -->

# 🛠️ Phase 2 : On pratique !

Créer un CV compatible ATS avec **Typst**

---

## 🛠️ C'est quoi Typst ?

Un outil de mise en page **moderne** et **gratuit** :
- 🌐 Utilisable en ligne sur **[typst.app](https://typst.app)**
- ✍️ Vous écrivez du **texte** → Typst génère un **PDF** professionnel
- 🎨 Des **templates** prêts à l'emploi pour les CV
- ⚡ Résultat visible en **temps réel**

### Pourquoi Typst plutôt que Word ?
- Le **contenu** est séparé de la **mise en forme**
- Vous ne risquez pas de « casser » la mise en page
- Les templates sont pensés pour être **ATS-friendly**

---

## 🚀 Étape 1 : Créer un compte

1. Allez sur **[typst.app](https://typst.app)**
2. Cliquez sur **Sign Up** (gratuit)
3. Créez votre compte avec email ou Google

![bg right:40% 90%](https://img.icons8.com/fluency/240/sign-up.png)

---

## 🚀 Étape 2 : Choisir un template

Depuis le Dashboard, cliquez sur **« Start from template »**

### 3 templates recommandés :

1. **[basic-resume](https://typst.app/universe/package/basic-resume/)**
   Simple, épuré, conçu pour passer les ATS ✅

2. **[brilliant-cv](https://typst.app/universe/package/brilliant-cv/)**
   Moderne, multilingue (🇫🇷 français !), injection de mots-clés ATS 🤖

3. **[guided-resume-starter-cgc](https://typst.app/universe/package/guided-resume-starter-cgc/)**
   Avec guide intégré pour vous accompagner pas à pas 📖

---

## 🚀 Étape 3 : Personnaliser

Une fois le template ouvert dans Typst :

1. **Remplacez** les informations d'exemple par les vôtres
2. Le panneau de droite montre le **résultat en direct**
3. Concentrez-vous sur le **contenu**, le template gère la mise en forme

### 💡 Conseils
- Commencez par vos **coordonnées** en haut
- Ajoutez vos **expériences** de la plus récente à la plus ancienne
- Listez vos **compétences** en reprenant les mots-clés des offres visées
- **Exportez en PDF** une fois satisfait (bouton en haut à droite)

---

<!-- _class: lead -->

# 🔁 Phase 3 : On reteste !

Votre nouveau CV fait-il mieux ?

---

## 🔁 Comparer les résultats

1. Exportez votre nouveau CV en **PDF** depuis Typst
2. Retournez sur le même site de test ATS utilisé avant
3. Uploadez votre **nouveau PDF**

### Comparez :

| | Avant | Après |
|---|---|---|
| Score global | ___ | ___ |
| Parsing correct | ❌ / ✅ | ❌ / ✅ |
| Sections détectées | ___ / 5 | ___ / 5 |
| Mots-clés trouvés | ___ | ___ |

---

## 📚 Pour aller plus loin

### Outils
- 🔗 [typst.app](https://typst.app) — éditeur en ligne gratuit
- 🔗 [resumeats.io](https://resumeats.io) — testeur ATS gratuit
- 🔗 [enhancv.com/resume-checker](https://enhancv.com/resources/resume-checker/) — analyse détaillée

### Templates Typst pour CV
- 🔗 [basic-resume](https://typst.app/universe/package/basic-resume/)
- 🔗 [brilliant-cv](https://typst.app/universe/package/brilliant-cv/)
- 🔗 [guided-resume-starter-cgc](https://typst.app/universe/package/guided-resume-starter-cgc/)

### Ce dépôt
- 🔗 [github.com/.../ats-ready-resume-workshop](https://github.com/)

---

<!-- _class: lead -->

# ❓ Questions ?

Merci pour votre participation ! 🙏

**Retrouvez toutes les ressources sur le dépôt GitHub**
