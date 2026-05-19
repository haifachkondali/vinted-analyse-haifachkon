# 📸 Comment ajouter les photos

Pour afficher les photos de tes articles dans le dashboard :

1. Trouve le dossier `haifachkon - member profile _ Vinted_files` (là où tu as sauvegardé la page HTML)
2. Crée un dossier `images/` dans ce repo cloné
3. Copie tous les fichiers `.webp` dedans :

```powershell
mkdir images
Copy-Item "C:\chemin\vers\haifachkon - member profile _ Vinted_files\*.webp" -Destination "images\"
git add images/
git commit -m "Ajout photos articles"
git push
```

Le dashboard chargera automatiquement les photos depuis le dossier `images/`.
