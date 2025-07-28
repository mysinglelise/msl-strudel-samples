# MSL Strudel Samples

Collection de samples audio personnels pour [Strudel](https://strudel.cc/) - l'environnement de live coding musical dans le navigateur.

> 🎵 **Samples for Strudel** - Partagez et utilisez ces samples dans vos compositions Strudel !

## 🎵 Samples disponibles

### Pour Strudel (extraits courts)
- **magicfriend** - `magicfriend.wav`
- **themoonvocoder** - `themoonvocoder-3.wav` 
- **silverfever** - `silverfever.wav`
- **glass** - `glass.wav`

##  Utilisation dans Strudel

### Méthode recommandée (testée et fiable)
```javascript
samples({
  magicfriend: 'https://mysinglelise.github.io/msl-strudel-samples/magicfriend.wav',
  themoonvocoder: 'https://mysinglelise.github.io/msl-strudel-samples/themoonvocoder-3.wav',
  silverfever: 'https://mysinglelise.github.io/msl-strudel-samples/silverfever.wav',
  glass: 'https://mysinglelise.github.io/msl-strudel-samples/glass.wav'
})

// Puis utilisez vos samples :
s("magicfriend")
s("themoonvocoder") 
s("silverfever")
s("glass")
```

### Méthode courte GitHub (peut nécessiter plusieurs essais)
```javascript
samples('github:mysinglelise/msl-strudel-samples')
s("magicfriend")
```

## 📁 Structure du repository

```
msl-strudel-samples/
├── README.md
├── strudel.json          # Configuration pour Strudel
├── magicfriend.wav       # Sample court
├── themoonvocoder-3.wav  # Sample court
├── silverfever.wav       # Sample court
└── glass.wav             # Sample court
```

## 🎧 Vocal tracks 

Les tracks de voix sont disponibles pour téléchargement :
- [Magic Friend - version complète](https://mysinglelise.github.io/msl-strudel-samples/magicfriend-full.mp3) *(si disponible)*
- [Silver Fever - version complète](https://mysinglelise.github.io/msl-strudel-samples/silverfever-full.mp3) *(si disponible)*

*Note : Les tracks de voix sont trop longues pour être utilisées directement dans Strudel mais peuvent être téléchargées pour écoute.*


### Problèmes connus
- La méthode `samples('github:...')` peut parfois échouer due au cache
- Dans ce cas, utilisez toujours la méthode avec URLs complètes
- Les samples peuvent prendre quelques secondes à se charger la première fois

## 📝 À propos

Ces samples sont créés par mysinglelise pour partager mes compositions musicales avec la communauté Strudel.

---

*Créé pour [Strudel](https://strudel.cc/) - Live coding musical dans le navigateur*
