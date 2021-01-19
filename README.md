# setup Tailwind CSS

postccs.config.js : fichier configuration (analyse des fichier css, ajout des plugins (tailwindcss, autoprefixer))

tailwind.config.js : fichier configuration (effectuer des actions avec tailwindcss)

npm run build : compilation css

npm run watch : surveiller notre fichier css a chaque changement

npm run production (version de production: Purge CSS)

Les dépendances :

    "autoprefixer": "^10.2.1",
    "cross-env": "^7.0.3",
    "postcss": "^8.2.4",
    "postcss-cli": "^8.3.1",
    "tailwindcss": "^2.0.2"