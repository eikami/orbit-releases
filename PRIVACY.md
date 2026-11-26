# Politique de confidentialité d'Orbit

*Dernière mise à jour : 26 novembre 2026 (version 0.4.0)*

Orbit est un navigateur pour Windows qui permet de chercher avec Google, ChatGPT, Claude et Gemini.
**Orbit ne collecte aucune donnée personnelle.** Il n'existe pas de compte Orbit ni de serveur Orbit :
rien de ce que vous faites dans l'application ne nous est envoyé.

## Ce qui est stocké sur votre ordinateur (et uniquement là)
- **Vos préférences** : moteur par défaut, thème, options d'ouverture dans le navigateur.
- **L'historique de vos recherches**, si l'option « Enregistrer l'historique » est activée (elle peut être désactivée dans le menu ☰).
- **Les cookies et sessions des sites que vous visitez** (par exemple votre connexion à ChatGPT, Claude ou Gemini), comme dans n'importe quel navigateur.
- **Les logos des moteurs de recherche et des raccourcis de sites**, mis en cache pour l'affichage.
- **Vos onglets ouverts** (pour les rouvrir au prochain lancement, option désactivable), vos raccourcis « / »,
  vos raccourcis de sites et votre fond d'écran personnalisé.

En **navigation privée**, rien de tout cela n'est enregistré : l'historique n'est pas conservé et les cookies
sont effacés à la fermeture de la fenêtre.

Ces données restent sur votre appareil. Vous pouvez les supprimer à tout moment depuis le menu ☰ :
« Effacer l'historique » ou « Effacer données et connexions ».

## Connexions réseau effectuées par Orbit
- **Les sites que vous ouvrez** (Google, ChatGPT, Claude, Gemini ou tout autre site). Vos identifiants sont
  saisis directement sur ces sites officiels : Orbit ne les lit pas et ne les conserve pas. Ces services
  appliquent leurs propres politiques de confidentialité.
- **Le téléchargement des logos** des moteurs depuis leurs sites officiels (google.com, openai.com, claude.ai, gstatic.com)
  et des icônes des sites ajoutés en raccourci, depuis ces sites.
- **Le bloqueur de publicités** (activé par défaut, désactivable) télécharge des listes de filtres publiques
  du projet open source Ghostery. Le filtrage se fait ensuite entièrement sur votre ordinateur.
- **Les fonctions IA** (clic droit « Demander à l'IA », « Résumer la page », mode Comparer) envoient le texte
  sélectionné, le contenu de la page ou votre question **uniquement à l'IA que vous choisissez**, et seulement
  quand vous le demandez, comme si vous le copiiez vous-même dans ChatGPT, Claude ou Gemini.
- **La recherche de mises à jour** (version téléchargée depuis GitHub uniquement) : Orbit consulte la page
  des versions sur github.com. Comme pour toute visite d'un site, GitHub reçoit votre adresse IP.
  La version Microsoft Store est mise à jour par le Store.

Orbit n'intègre aucun outil de statistiques, de publicité ou de suivi.

## Enfants
Orbit ne s'adresse pas spécifiquement aux enfants et ne collecte aucune donnée les concernant.

## Supprimer toutes vos données
Effacez-les depuis le menu ☰, ou désinstallez Orbit puis supprimez le dossier `%APPDATA%\orbit-browser`
s'il existe encore.

## Contact
Pour toute question : ouvrez une demande (« issue ») sur https://github.com/eikami/orbit-releases/issues

---

# Orbit Privacy Policy (English)

*Last updated: November 26, 2026*

Orbit is a Windows browser for searching with Google, ChatGPT, Claude and Gemini.
**Orbit does not collect any personal data.** There is no Orbit account and no Orbit server.

- **Stored locally only:** preferences, optional search history, cookies/sessions of the websites you visit,
  and cached search-engine logos. You can delete them at any time from the ☰ menu.
- **Network connections:** the websites you open (you sign in directly on the official sites; Orbit never
  reads or stores your credentials), engine and shortcut logos downloaded from the related websites, public
  ad-blocking filter lists (Ghostery open-source project; filtering then happens locally), and — for the
  GitHub version only — update checks on github.com. The Microsoft Store version is updated by the Store.
- **AI features** (right-click "Ask AI", "Summarize page", Compare mode) send the selected text, page content
  or your question only to the AI you choose, and only when you ask.
- **Private windows** keep no history, and their cookies are erased when the window is closed.
- **No analytics, advertising or tracking.**
- **Contact:** https://github.com/eikami/orbit-releases/issues
