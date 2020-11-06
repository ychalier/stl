# Hébergement de modèles 3D

Ce dépôt héberge des modèles 3D au format STL visant à être intégrés dans des pages HTML via le moteur de rendu de GitHub. Pour cela :

1. Ajouter le `.stl` au dépôt (si possible avec un nom explicite)
2. Dans le gabarit HTML, inclure la ligne suivante :
   ```html
   <script src="https://embed.github.com/view/3d/ychalier/stl/main/<path_to_file>"></script>
   ```

Voir la documentation de GitHub [3D File Viewer › Embedding your model elsewhere](https://docs.github.com/en/free-pro-team@latest/github/managing-files-in-a-repository/3d-file-viewer#embedding-your-model-elsewhere) pour plus de détails.
