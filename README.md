# Guide d'installation des mods Minecraft Fabric sur macOS

Ce guide vous explique comment installer des mods Minecraft utilisant le modding framework Fabric sur un système macOS. Fabric est un système léger et flexible qui permet aux développeurs de créer des mods pour Minecraft. Suivez les étapes ci-dessous pour installer des mods Fabric sur votre client Minecraft sur macOS.

Vous ètes un utilisateur Windows pas de soucis allez [ici](https://github.com/MrPantoufle/Netheria-mods).

## Prérequis

Avant de commencer, assurez-vous d'avoir les éléments suivants :

1. Le launcher officiel Minecraft installé sur votre ordinateur.
2. La version 1.20.1 de Minecraft installer.
3. Le fichier d'installation Fabric Loader. Vous pouvez le télécharger depuis le site officiel de Fabric : [https://fabricmc.net/use/](https://fabricmc.net/use/).
4. Le fichier compressé des mods Fabric (fichiers `Netheria-mods-v.1.0.zip`) situer [ici](https://github.com/MrPantoufle/Netheria-mods/releases/tag/1.0.0).
5. Le fix de simple voice chat (fichiers `simple-voicechat-fix.zip`) situer [ici](https://github.com/MrPantoufle/Netheria-mods/releases/tag/1.0.0)

## Étapes d'installation

1. **Installation de Fabric Loader :**
   - Lancer au moins une fois minecraft en **1.20.1**.
   - Assurez-vous que Minecraft n'est plus en cours d'exécution.
   - Ouvrez le fichier d'installation de Fabric Loader que vous avez téléchargé.
   - Sélectionnez la dernière version des mappings, la dernière version du loader et votre dossier ou se situe minecraft.
   - Cochez (créer un profile) Cliquez sur le bouton "Install".
   - Une fois l'installation terminée, vous devriez voir un nouveau profil Fabric dans votre lanceur Minecraft.

3. **Création d'un dossier de mods :**
   - Ouvrez le lanceur Minecraft.
   - Sélectionnez le profil Fabric que vous venez de créer.
   - Démarrez Minecraft pour générer les dossiers et fichiers nécessaires.
   - Quittez Minecraft.

4. **Installation des mods :**
   - Ouvrez le Finder sur votre Mac.
   - Appuyez sur la combinaison de touches `Commande + Majuscule + G` pour ouvrir la boîte de dialogue "Aller au dossier".
   - Entrez `~/Library/Application Support/minecraft` dans la boîte de dialogue et cliquez sur "Aller".
   - À l'intérieur du dossier `minecraft`, vous devriez voir un nouveau dossier appelé `mods`.
   - Copiez les fichiers de mod Fabric (extension `.jar`) dans le dossier `mods`.
   - Si vous le souhaitez vous pouvez rajouter les mods optionnelle qui sont détaillé ici :
     1. `continuity.jar` sert à avoir certainne texture de minecraft qui se rejoinne compensant le manque d'optifine.
     2. `shift scroll fix.jar` à régler l'imposibilité de sprinter et de changer d'item sur mac.
     3. `replaymod.jar` à enregistrer vos séssion de jeux.
     4. `Wi Zoom.jar` à avoir le zoom optifine.

5. **Lancement de Minecraft avec les mods :**
   - Lancez le shell qui vient du téléchargement de `simple-voicechat-fix.zip`.
   - 🚨❗un terminal s'ouvre ne le fermer pas.
   - Le launcher de minecraft s'ouvre.
   - Sélectionnez le profil Fabric que vous avez créé précédemment.
   - Cliquez sur le bouton "Jouer" pour démarrer Minecraft avec les mods installés.
   - Les mods devraient maintenant être chargés et prêts à être utilisés dans votre partie.

C'est tout ! Vous avez réussi à installer des mods Minecraft Fabric sur macOS. Hâte de vous voir sur le serveur.

**Note :** Nhésitez pas à demander de l'aide en créant un ticket dans le salon dédié sur discord.
