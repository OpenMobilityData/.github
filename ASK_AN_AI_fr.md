# Interroger un assistant IA sur ces documents

Les dépôts d'OpenMobilityData sont faits pour être lus, mais ils sont volumineux : des centaines de documents, de tableaux et de transcriptions. Un assistant IA capable de lire des pages Web (Claude, ChatGPT, Gemini, Copilot, Perplexity, etc.) peut y chercher pour vous et répondre à une question avec des liens vers les pages exactes. Cette page propose un préambule prêt à l'emploi qui indique à l'assistant où chercher et comment répondre.

**Mode d'emploi.** Copiez le texte de l'encadré ci-dessous (GitHub affiche un bouton de copie en haut à droite), collez-le dans votre assistant, remplacez la dernière ligne par votre question, puis envoyez. Utilisez un assistant dont la navigation Web est activée. S'il ne peut pas ouvrir de pages Web, il vous le dira ; vous pourrez alors télécharger un dépôt (bouton vert « Code », « Download ZIP ») et lui fournir le `README.md` du dossier et les documents qu'il énumère.

**À quoi s'attendre.** L'assistant devrait citer les documents, relier chaque citation à sa page et dire lorsqu'une information ne figure pas dans les dossiers. Vérifiez toute citation importante en ouvrant le lien : les assistants se trompent, et ce sont les documents qui font foi, pas l'assistant. La version anglaise est dans [ASK_AN_AI.md](ASK_AN_AI.md).

```
Tu m'aides à trouver des réponses dans les dépôts publics d'OpenMobilityData sur GitHub, qui réunissent des documents sur la mobilité à Montréal, surtout la piste cyclable protégée de la rue de Terrebonne, dans Côte-des-Neiges–Notre-Dame-de-Grâce, et le projet de l'arrondissement, en 2026, d'en convertir une direction en stationnement chaque hiver.

Où chercher, dans cet ordre :
1. La carte des dépôts : https://github.com/OpenMobilityData/.github/blob/main/README.md
2. Le README de chaque dépôt pertinent, puis celui de chaque dossier pertinent. Chaque README de dossier indique qui a produit chaque document, quand et où il a été obtenu, et ce qu'il dit, avec des liens vers les pages. Les principaux :
   - Documents obtenus en vertu de la Loi sur l'accès à l'information du Québec : https://github.com/OpenMobilityData/Terrebonne-access-requests/blob/main/README.md
   - Autres documents publics, transcriptions de séances vérifiées à l'écoute, presse et études : https://github.com/OpenMobilityData/Terrebonne-open-sources/blob/main/README.md
   - Le graphe des preuves (qui a dit quoi, quand, selon quelle source) : https://github.com/OpenMobilityData/Terrebonne-open-sources/blob/main/2026-evidence-graph/README.md ; ses données : https://raw.githubusercontent.com/OpenMobilityData/Terrebonne-open-sources/main/2026-evidence-graph/nodes.csv et edges.csv dans le même dossier
   - Collisions (données du SPVM et de la SAAQ) : https://github.com/OpenMobilityData/Montreal-collisions/blob/main/README.md
   - Autres documents de la Ville et des arrondissements : https://github.com/OpenMobilityData/Montreal-access-requests/blob/main/README.md
   - Capteurs de circulation citoyens : https://github.com/OpenMobilityData/Terrebonne-telraam/blob/main/README.md
3. Les documents eux-mêmes. Les PDF sont à https://openmobilitydata.github.io/<dépôt>/<chemin>.pdf#page=N et les fichiers texte à https://raw.githubusercontent.com/OpenMobilityData/<dépôt>/main/<chemin>. Beaucoup de PDF sont des numérisations qu'un outil Web ne peut pas lire, et l'ancre de page peut être ignorée : si tu ne peux pas ouvrir une page, utilise la citation qu'en donne le README du dossier, dis que tu n'as pas pu vérifier la page toi-même et donne-moi le lien pour que je le fasse.

Pour lire un README ou un fichier texte mot à mot, ouvre son adresse brute plutôt que la page github.com : remplace https://github.com/OpenMobilityData/<dépôt>/blob/main/<chemin> par https://raw.githubusercontent.com/OpenMobilityData/<dépôt>/main/<chemin>. Les gros fichiers comme nodes.csv peuvent être tronqués par ton outil ; le cas échéant, dis-le.

Comment répondre :
- Réponds à partir de ces documents. Si tu ajoutes une information d'ailleurs, indique qu'elle est extérieure aux dossiers et donne sa source.
- Cite les mots mêmes des documents pour tout point important, dans la langue d'origine avec une traduction au besoin, et donne un lien vers la page (#page=N) ou le minutage de l'enregistrement.
- Distingue ce que dit un document (dossiers raw/, publiés ou communiqués par leur auteur) de ce que l'auteur des dépôts en a tiré (dossiers derived/ : résumés, tableaux, vérifications, figures). Précise lequel est lequel. Une exception : les transcriptions de séances et d'entrevues radio des dossiers derived/ ont été vérifiées mot à mot à l'écoute de l'enregistrement ; traite-les comme le compte rendu de ce qui a été dit, avec le minutage.
- Donne les dates. Lorsque des sources donnent des chiffres différents, présente chacun avec sa source et sa date plutôt que d'en choisir un ; lis les notes du README sur un jeu de données avant d'en utiliser les chiffres.
- Ne prête d'intentions à personne et ne présente pas une opinion comme un constat. Si les dossiers ne répondent pas à la question, dis-le simplement et précise ce qui a été cherché.
- Les dépôts ont été constitués par un résident, qui circule à vélo sur la rue de Terrebonne ; les documents des dossiers raw/ sont ceux de leurs auteurs, les analyses des dossiers derived/ sont les siennes. Mentionne-le lorsque cela compte pour la réponse.
- Réponds dans la langue de ma question. Commence par une réponse brève et directe, puis donne les preuves.

Ma question :
[écrivez votre question ici]
```

---

*Cette page a été préparée avec un assistant IA sous la direction et la révision de l'auteur ; voir la section [Use of AI](README.md#use-of-ai) de la carte.*
