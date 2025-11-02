🍷 AI Wine Advisor
Votre sommelier personnel alimenté par l’IA (exécution locale)
🚀 Description

AI Wine Advisor est une application web locale qui recommande automatiquement 3 vins réels disponibles sur Vivino en fonction :

du plat principal,

de l’ambiance/occasion,

du budget,

et éventuellement d’une région viticole française.

L’application s’appuie sur l’API Gemini de Google pour générer des recommandations précises et formatées en JSON.

Tout fonctionne en local, directement dans votre navigateur — aucune installation de serveur n’est requise.

🧰 Fonctionnalités principales

✅ Interface moderne et responsive (Tailwind CSS)
✅ Chargement animé et cartes de vins détaillées
✅ Génération de recommandations IA (3 vins réels sur Vivino)
✅ Filtrage par budget et région
✅ Affichage dynamique des résultats avec effets visuels

💻 Installation locale
1. Télécharger le projet

Téléchargez le fichier HTML principal :

ai-wine-advisor.html


Ou clonez votre dépôt :

git clone https://github.com/votre-utilisateur/ai-wine-advisor.git
cd ai-wine-advisor

2. Créer une clé API Gemini

Rendez-vous sur https://makersuite.google.com/app/apikey

Connectez-vous avec un compte Google

Cliquez sur Create API key

Copiez la clé générée (format : AIzaSyA...)

3. Insérer la clé API

Ouvrez le fichier ai-wine-advisor.html dans un éditeur de texte.
Repérez la ligne suivante (en haut du <script> principal) :

const GEMINI_API_KEY = 'VOTRE_CLE_API_ICI';


👉 Remplacez 'VOTRE_CLE_API_ICI' par votre propre clé API.

⚠️ Ne partagez jamais publiquement votre clé API.
Si vous publiez le projet sur GitHub, laissez la valeur vide ou indiquez un placeholder :

const GEMINI_API_KEY = ''; // ← à remplir avec votre clé personnelle

4. Lancer l’application

Ouvrez simplement le fichier HTML dans votre navigateur :

Sous Windows : double-cliquez sur le fichier

Sous macOS/Linux : clic droit → “Ouvrir avec” → votre navigateur préféré

💡 L’application fonctionne entièrement en local (aucun backend nécessaire).
Elle communique directement avec l’API Gemini via HTTPS.

⚙️ Technologies utilisées

HTML5 / JavaScript ES6

TailwindCSS CDN

Google Gemini API (v1beta)

🔒 Sécurité

La clé API est stockée en clair uniquement pour un usage local.

Si vous souhaitez héberger l’application en ligne, vous devez protéger la clé API côté serveur (via un proxy ou un backend sécurisé).

📄 Licence

Projet open-source à usage éducatif et expérimental.
Les vins recommandés sont issus de la base Vivino, et leurs informations peuvent varier dans le temps.
