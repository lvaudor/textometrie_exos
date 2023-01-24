Ce dossier contient le **tutoriel learnr** pour le cours "Textométrie avec R".

Il est calibré pour 

- **10h30 de cours, en 3 séances (3 *3h30)** si non suivi d'une initiation à R,
- **6h en 2 séances sinon**.

Le document **textometrie_ministereco.Rmd** comprend les commandes utilisées pour scraper et mettre en forme le corpus. Il génère notamment les jeux de données suivants:

- **tib_meta**: les métadonnées (lien, titre, ministre, date)
- **tib_docs**: les métadonnées, associées au texte brut
- **tib_textes**: les métadonnées, associées au texte auquel on a appliqué un pré-traitement visant à identifier les mots propres
- **tib_lemmes**: les lemmes (issus de la tokenisation de tib_textes et jointure avec un lexique)

Les données ne sont pas directement incluses dans le repo github car trop volumineuses. Elles sont accessibles en suivant les liens listés [ici](https://perso.ens-lyon.fr/lise.vaudor/datasets/ministereco/).