# Lemmatisation et POS par LLM

Annoter les langues anciennes (GRC, HYE, KAT, SYC) par API, puis évaluer le résultat contre une vérité terrain. 
Le code d'origine est dans XXXXX/XXXXXX/XXXXXX. 

## Règles 
- Python : ne jamais installer via pip directement. Utilise "uv add"
- L'environnement de travail est le venv du dossier XXXXX. 
- La clef API est dans XXXXX. 
- Ne jamais modifier les scripts d'origine du repo.
- Un agent ne lit jamais les données brutes et le tagset, ces tâches sont réservées au script développé. 

## Travail des agents 
- Pour annoter utilise l'agent annotateur. 
- Pour valider les résultats, utilise l'agent validateur. 
- Lance le validateur uniquement quand l'agent annotateru a terminé son travail. 

## Repères 
- GRC = grec ancien
- HYE = arménien ancien ... 
- [expliquer la structure du dossier dataset]
- modèles openrouter : le nom des modèles suit la logique "éditeur/modèle" 