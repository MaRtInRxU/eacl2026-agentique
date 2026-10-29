# AGENTS.md - Directives pour les agents IA

ce travail s'inscrit dans une recherche en humanités numériques de pointe sur le grec ancien

le fichier de données se trouve ici : data/corpus/train/GRC_train.tsv

form	lemma	pos
ταὐτόν	ὁ@αὐτός	DET@PRO+Dem
οἶμαι	οἴομαι (–ω)	V
πέπονθας	πάσχω	V
ταῖς	ὁ	DET
μελίσσαις	μέλισσα	N+Com

assure toi que la sortie est bien un tableau, que les tags appartiennent à la liste

tu dois lemmatiser puis post-tagger les données que voilà. 

il faut que ce soit un tableau de trois colonnes respectivement form ; lemma ; pos format tsv 