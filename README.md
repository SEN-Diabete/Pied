# 🦶 Mon Pied, Mon Capital — Séné Diabète

Un outil web interactif et pédagogique conçu pour la **prévention du pied diabétique au Sénégal**. 

Développé pour être vendu en **marque blanche (white-label)** aux pharmacies, mutuelles de santé et ONG, cet outil permet au patient de s'auto-évaluer en 5 minutes et d'obtenir un bilan de risque personnalisé.

## 🎯 Le Problème
Au Sénégal, le pied diabétique est la première cause d'amputations non traumatiques. Pourtant, **50 % de ces amputations sont évitables** grâce à la prévention et à l'éducation thérapeutique. Les patients manquent souvent d'outils simples pour savoir quand consulter.

## 💡 La Solution
Une application web mobile-first qui guide le patient dans l'inspection de ses pieds :
1. **Carte interactive** : 6 vues photographiques (Dessus, Plante, Profils, Orteils, Chaussures).
2. **Éducation visuelle** : En cliquant sur une zone, le patient voit une photo de la complication possible (ulcère, ongle incarné, fissure, cor).
3. **Éducation audio** : Des conseils pré-enregistrés en **Wolof** (et bientôt Pulaar) pour les patients à faible littératie.
4. **Bilan personnalisé** : Un score de risque (Vert / Orange / Rouge) indique au patient s'il doit consulter en urgence (24h) ou simplement surveiller.

## 🔒 Garanties & Conformité (CDP)
*   **100 % Anonyme** : Aucune donnée personnelle n'est collectée (pas de nom, pas de numéro, pas de cookie).
*   **Zéro base de données** : Aucune information ne quitte le navigateur du patient.
*   **Conforme à la loi sénégalaise (2008-12)** : Zéro risque réglementaire pour les structures partenaires.
*   **Fonctionne hors-ligne** : Une fois chargé, l'outil ne nécessite aucune connexion internet.

## 🛠️ Stack Technique
*   **HTML5 / CSS3 / JavaScript (Vanilla)** : Fichier unique (`index.html`) ultra-léger, sans aucune dépendance (pas de React, pas de Node.js).
*   **Hébergement** : Compatible avec GitHub Pages, Cloudflare Pages, ou tout serveur statique local (Sonatel, ADIE).
*   **Assets** : Images et sons stockés en local dans les dossiers `/photos` et `/audios`.

## 🚀 Déploiement & Installation
1. Clonez ce repository.
2. Ajoutez vos propres images dans le dossier `/photos` (format carré, optimisé pour le web).
3. Ajoutez vos fichiers audio en Wolof ou Pulaar dans le dossier `/audios`.
4. Modifiez le fichier `index.html` pour y insérer le lien de votre logo (ou fichier base64).
5. Ouvrez `index.html` dans un navigateur ou déployez sur GitHub Pages.

## 💼 Modèle Économique (B2B)
Cet outil est pensé pour être **white-labelisé**. Une pharmacie ou une mutuelle peut l'acquérir sous forme de licence annuelle, y apposer son logo, et le diffuser à ses patients via un QR code. 

## 👩🏾‍⚕️ Auteure
Conçu par une spécialiste en éducation thérapeutique, avec une approche centrée sur le patient et adaptée au contexte culturel et linguistique sénégalais.