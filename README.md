# Véramique
Site statique généré avec Github Pages Gallery, qui utilise Thumbsup & Github Actions.

#### Créer un nouvel album
1. Se rendre dans le dossier "[gallery](https://github.com/ici-be/veramique/tree/master/gallery)" du projet
2. Cliquer sur le bouton "Add file" puis "Create new file" (à droite, près des "...")
3. Ecrire par exemple `Expo 2021/.gitkeep` dans le champ texte "Name your file..."
4. Cliquer sur le bouton vert "Commit Changes", en bas

#### Ajouter des photos
1. Se rendre dans le dossier "[gallery](https://github.com/ici-be/veramique/tree/master/gallery)" du projet, ou dans l'un de ses sous-dossiers correspondants aux albums créés
2. Cliquer sur le bouton "Add files", puis "Upload files"
3. Sélectionner les photos à uploader. Une fois que l'upload est terminé, cliquer sur le bouton vert "Commit Changes". Le site se mettra à jour en une à deux minutes environ

#### Supprimer une photo
1. Se rendre dans le dossier "[gallery](https://github.com/ici-be/veramique/tree/master/gallery)" du projet, ou dans le sous-dossier "album" qui contient cette photo
2. Cliquer sur le nom de la photo à supprimer
3. Cliquer sur le bouton avec une icône de poubelle ("Delete this file" apparaît au survol)
4. Confirmer la suppression en cliquant sur le bouton vert "Commit Changes"

#### Supprimer un album ainsi que toutes ses photos
1. Se rendre dans le dossier "[gallery](https://github.com/ici-be/veramique/tree/master/gallery)" du projet, puis dans le sous-dossier "album" à supprimer. A ne pas faire pour le dossier "gallery" lui-même, sinon le site va casser...
2. Cliquer sur le bouton "...", puis sur "Delete directory"
3. Confirmer la suppression en cliquant sur le bouton vert "Commit Changes"

#### Divers
- **Descriptions des photos** Quand on les affiche sur le site, certaines photos ont pour description "Olympus digital camera". C'est le champ "Description" des métadonnées des photos qui est récupéré et affiché. Il vaut mieux soit effacer cette donnée avant l'upload de la photo, ou en profiter pour mettre une description plus pertinente.
- **Changer le titre** Ouvrir le fichier config.json avec le bouton d'édition (crayon), modifier la valeur de "title" puis cliquer sur "Commit changes"
- **Changer la citation de bas de page** Ouvrir le fichier custom.css et modifier la phrase en question
- **Photo d'album** la première par ordre alphabétique. Préfixer d'un underscore "_" pour plus de facilié
