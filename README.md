**Telecharger les JSON**
- Cliquer sur le bouton vert **Code**
- Dans l'onglet **local**, cliquer sur **Download Zip**
- Sur votre ordinateur, clic droit sur le fichier Zip, extraire

**Ouvrir le fichier JSON ''histoire_Halloween_Edition.json'**
- Option 1: Avec le bloc note (Mais le code ne sera pas coloré et peu lisible)
- Option 2: [Avec le logiciel Microsoft Visual Studio Code (Gratuit)](https://code.visualstudio.com/)
- Option 3: [Avec le logiciel Notepad++ (Gratuit)](https://notepad-plus-plus.org/downloads/)

**Commencer à éditer le fichier**
- **“identifiant”** : un nom unique associé à chaque page
- **“image”** : le nom de l’image utilisée comme décor (Formats acceptés .jpg .png .gif). Elle doit se situer dans le dossier ''backgrounds/Halloween/''.
- **“perso”** : le nom de l’image utilisée pour un personnage, un groupe de personnages, des objets ou autres (Formats acceptés .jpg .png .gif). Elle doit se situer dans le dossier ''persos/Halloween/''.
- **“texte”** : le texte qui s’affiche. < p >Utiliser ces balises pour créer un paragraphe.< /p > < p >Mettre des mots en < b >**gras**< /b >, < i >*italique*< /i >, etc…< /p >
- **“options”** : la liste des différentes options proposées au joueur. Pour chaque option :
      - “question” : le texte de la question.
      - “vers” : Identifiant de la page vers laquelle pointe la question.
      - “condition” : Liste des conditions qui doivent être remplies pour que ça fonctionne. Un condition peut avoir deux valeurs: “true” (si le joueur a le statut) soit “false” (si le joueur n’a jamais eu le statut, ou s’il l’a perdu).
      - “consequence” : la liste des statuts qui sont créés ou supprimés quand on clique sur ce choix.

**Organiser les fichiers dans les dossiers**
- Le dossier ''backgrounds/Halloween/'' est pour les décors
- Le dossier ''persos/Halloween/'' est pour les assets (personnages, objets)

**Dimension des images**
- 900 pixels de large obligatoire
- La hauteur est libre mais doit quand même tourner entre 450 et 700 pixels de préférence.

**Debugage à l'aide de la console de debugage de Recro**
- [La console de deboguage est disponible ici](https://github.com/Grinouille/dating-lubien) (Suivre le README.md pour l'installation)
