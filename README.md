# Hébergement de modèles 3D

Ce dépôt héberge des modèles 3D au format STL visant à être intégrés dans des pages HTML via le moteur de rendu de GitHub. Pour cela :

1. Ajouter le `.stl` au dépôt (si possible avec un nom explicite)
2. Dans le gabarit HTML, inclure la ligne suivante :
   ```html
   <script src="https://embed.github.com/view/3d/ychalier/stl/main/<path_to_file>"></script>
   ```
   Pour s'assurer que les dimensions restes correctes sous le framework [Spectre.css](https://picturepan2.github.io/spectre/) :
   ```html
   <p>
     <div class="video-responsive video-responsive-16-9">
       <script src="https://embed.github.com/view/3d/ychalier/stl/main/<path_to_file>?height=180&width=320"></script>
     </div>
   </p>
   ```

Voir la documentation de GitHub [3D File Viewer › Embedding your model elsewhere](https://docs.github.com/en/free-pro-team@latest/github/managing-files-in-a-repository/3d-file-viewer#embedding-your-model-elsewhere) pour plus de détails.
