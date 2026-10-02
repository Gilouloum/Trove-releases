# Trove Privacy Policy

*Last updated: 2 October 2026* · [Version française plus bas](#politique-de-confidentialité-de-trove)

Trove runs on your computer. Your photos, videos, file names, folders, faces, people's names and edits never leave it. There are no accounts, no ads and no cookies, and nothing is ever sold.

A few features do talk to outside services. This page lists every one of them, what they receive, and how to turn them off.

## Who is responsible

Trove is made by Yannis Morin, an individual developer based in France, who is the data controller for the processing described here.

Contact: **[trovephotos@gmail.com](mailto:trovephotos@gmail.com)**

## 1. Anonymous usage statistics ("Help improve Trove")

**What is sent.** When the app opens and when it closes, Trove sends one small message containing:

- a random install ID (generated on your computer, not linked to your name or email, and replaced every 13 months)
- the event type (app opened or session ended) and the session length
- the number of files, folders, Best Of photos and pinned photos in your library
- the Trove version and operating system (Windows or macOS)

**What is never sent.** Photos, videos, thumbnails, file names, folder names, paths, locations, faces, people's names, search queries, or anything else from your library.

**Why.** To know how many people use Trove and roughly how, so I can decide what to fix and build next. It is used only for these statistics: never for advertising, never combined with other data, never shared or sold.

**Legal basis.** Legitimate interest (Article 6(1)(f) GDPR) in measuring the app's audience. The install ID stored on your computer is covered by the exemption for audience measurement in Article 82 of the French Data Protection Act, as set out by the CNIL. This is why the ping is on by default but can be turned off at any time.

**Where it is stored.** In Google Firebase (Cloud Firestore), with Google acting as a processor on my behalf. Google may process data outside the European Union. Those transfers are covered by the EU-US Data Privacy Framework and Google's Standard Contractual Clauses. Like any internet request, the message reveals your IP address to Google when it is sent. Trove does not record it.

**How long.** Each event is deleted 25 months after it is sent.

**Your choice.** Trove tells you about this on first launch, and nothing is sent until you have seen that notice. You can turn it off there, or at any time in **Settings → Help improve Trove**. Once it is off, nothing more is sent.

## 2. Place names for your photos (OpenStreetMap)

When a photo or video has GPS coordinates, Trove looks up its country, region and city using OpenStreetMap's Nominatim service. Only the coordinates are sent, rounded to about 1 km, never the photo itself. Results are saved on your computer, so each area is looked up only once.

This is needed for the location folders to work. The service is run by the OpenStreetMap Foundation ([privacy policy](https://osmfoundation.org/wiki/Privacy_Policy)).

## 3. The Globe's map imagery (Esri)

When you open the Globe, the satellite imagery, place labels and, if you turn on 3D terrain, elevation data are downloaded from Esri's ArcGIS servers. Esri receives your IP address and the map tiles requested, meaning the area you are looking at, but no photo data ([Esri privacy statement](https://www.esri.com/en-us/privacy/privacy-statements/privacy-statement)).

## 4. Updates (GitHub)

Trove checks [GitHub](https://github.com/Gilouloum/Trove-releases) for new versions and downloads them from there. GitHub receives your IP address and the app version ([GitHub privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)).

## Everything else stays on your computer

Face recognition, AI search, duplicate detection, the photo editor and PhotoMod all run entirely on your machine, using models that ship inside the app. Your library data is stored in your user profile (`%APPDATA%\Trove` on Windows, `~/Library/Application Support/Trove` on macOS) and nowhere else.

## Your rights

Under the GDPR you have the right to access, correct and delete your data, to object to its processing and to restrict it. Because the statistics carry no name or email, I cannot tell which events are yours on my own. To have yours deleted, send me your install ID: it is the `installId` field in the `filelinker-data.json` file in the folder above.

You can also lodge a complaint with the CNIL ([cnil.fr](https://www.cnil.fr)) or with the data protection authority of your country.

## Changes

If this policy changes, the new version will be published here with a new date at the top.

---

# Politique de confidentialité de Trove

*Dernière mise à jour : 2 octobre 2026*

Trove fonctionne sur votre ordinateur. Vos photos, vidéos, noms de fichiers, dossiers, visages, noms de personnes et retouches n'en sortent jamais. Il n'y a ni compte, ni publicité, ni cookie, et rien n'est jamais vendu.

Certaines fonctions communiquent toutefois avec des services extérieurs. Cette page les liste toutes, indique ce qu'ils reçoivent et comment les désactiver.

## Responsable du traitement

Trove est développé par Yannis Morin, développeur indépendant basé en France, responsable des traitements décrits ici.

Contact : **[trovephotos@gmail.com](mailto:trovephotos@gmail.com)**

## 1. Statistiques d'utilisation anonymes (« Aider à améliorer Trove »)

**Ce qui est envoyé.** À l'ouverture et à la fermeture de l'application, Trove envoie un petit message contenant :

- un identifiant d'installation aléatoire (généré sur votre ordinateur, non lié à votre nom ni à votre e-mail, et renouvelé tous les 13 mois)
- le type d'événement (ouverture ou fin de session) et la durée de la session
- le nombre de fichiers, de dossiers, de photos Best Of et de photos épinglées de votre bibliothèque
- la version de Trove et le système d'exploitation (Windows ou macOS)

**Ce qui n'est jamais envoyé.** Photos, vidéos, miniatures, noms de fichiers, noms de dossiers, chemins, lieux, visages, noms de personnes, recherches, ni quoi que ce soit d'autre provenant de votre bibliothèque.

**Pourquoi.** Pour savoir combien de personnes utilisent Trove et, en gros, comment, afin de décider quoi corriger et développer ensuite. Ces données servent uniquement à ces statistiques : jamais à la publicité, jamais croisées avec d'autres données, jamais partagées ni vendues.

**Base légale.** L'intérêt légitime (article 6.1.f du RGPD) à mesurer l'audience de l'application. L'identifiant stocké sur votre ordinateur relève de l'exemption de consentement prévue pour la mesure d'audience par l'article 82 de la loi Informatique et Libertés, telle que précisée par la CNIL. C'est pourquoi ce signal est activé par défaut mais désactivable à tout moment.

**Où sont stockées les données.** Chez Google Firebase (Cloud Firestore), Google agissant en tant que sous-traitant pour mon compte. Google peut traiter les données hors de l'Union européenne. Ces transferts sont encadrés par le Data Privacy Framework UE-États-Unis et les clauses contractuelles types de Google. Comme toute requête sur Internet, l'envoi révèle votre adresse IP à Google. Trove ne l'enregistre pas.

**Durée de conservation.** Chaque événement est supprimé 25 mois après son envoi.

**Votre choix.** Trove vous en informe au premier lancement, et rien n'est envoyé avant que vous ayez vu cet avis. Vous pouvez le désactiver à ce moment-là, ou à tout moment dans **Paramètres → Aider à améliorer Trove**. Une fois désactivé, plus rien n'est envoyé.

## 2. Noms de lieux pour vos photos (OpenStreetMap)

Quand une photo ou une vidéo contient des coordonnées GPS, Trove retrouve le pays, la région et la ville grâce au service Nominatim d'OpenStreetMap. Seules les coordonnées sont envoyées, arrondies à environ 1 km, jamais la photo elle-même. Les résultats sont enregistrés sur votre ordinateur, chaque zone n'est donc recherchée qu'une fois.

C'est nécessaire au fonctionnement des dossiers de lieux. Le service est exploité par l'OpenStreetMap Foundation ([politique de confidentialité](https://osmfoundation.org/wiki/Privacy_Policy)).

## 3. Les images du Globe (Esri)

Quand vous ouvrez le Globe, l'imagerie satellite, les noms de lieux et, si vous activez le relief 3D, les données d'altitude sont téléchargés depuis les serveurs ArcGIS d'Esri. Esri reçoit votre adresse IP et les tuiles de carte demandées, c'est-à-dire la zone que vous regardez, mais aucune donnée de vos photos ([déclaration de confidentialité d'Esri](https://www.esri.com/en-us/privacy/privacy-statements/privacy-statement)).

## 4. Mises à jour (GitHub)

Trove vérifie sur [GitHub](https://github.com/Gilouloum/Trove-releases) si une nouvelle version existe et la télécharge depuis ce site. GitHub reçoit votre adresse IP et la version de l'application ([déclaration de confidentialité de GitHub](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)).

## Tout le reste reste sur votre ordinateur

La reconnaissance faciale, la recherche par IA, la détection de doublons, l'éditeur photo et PhotoMod fonctionnent entièrement sur votre machine, avec des modèles inclus dans l'application. Les données de votre bibliothèque sont stockées dans votre profil utilisateur (`%APPDATA%\Trove` sous Windows, `~/Library/Application Support/Trove` sous macOS) et nulle part ailleurs.

## Vos droits

Le RGPD vous donne un droit d'accès, de rectification, d'effacement, d'opposition et de limitation. Comme les statistiques ne contiennent ni nom ni e-mail, je ne peux pas savoir seul quels événements sont les vôtres. Pour faire supprimer les vôtres, envoyez-moi votre identifiant d'installation : c'est le champ `installId` du fichier `filelinker-data.json`, dans le dossier indiqué ci-dessus.

Vous pouvez aussi introduire une réclamation auprès de la CNIL ([cnil.fr](https://www.cnil.fr)).

## Modifications

Si cette politique change, la nouvelle version sera publiée ici avec une nouvelle date en haut de page.
