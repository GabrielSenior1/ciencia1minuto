# vCard Digital — Mateo Villarreal Sanchez (@ciencia_en_1minuto)

Tarjeta de contacto móvil (vCard) optimizada para iPhone (iOS) y Android, configurada para desplegarse directamente en Firebase Hosting (`ciencia1minuto-24f9f`).

## Estructura del proyecto

```text
ciencia1minuto/
├── .firebaserc
├── .gitignore
├── firebase.json
├── README.md
└── public/
    ├── index.html              # vCard interactiva móvil (Deep Space + Modo Claro)
    ├── avatar.jpg              # Foto de perfil de Mateo
    ├── apple-touch-icon.png    # Icono para pantalla de inicio iOS
    ├── icon-512.png            # Icono PWA Android
    ├── manifest.json           # Configuración PWA standalone
    └── mateo-villarreal.vcf    # Archivo de contacto vCard 3.0 con foto embebida
```

## Subir a GitHub

```bash
git init
git add .
git commit -m "Agrega vCard móvil de Mateo Villarreal y config de Firebase Hosting"
git branch -M main
git remote add origin https://github.com/GabrielSenior1/ciencia1minuto.git
git push -u origin main
```

*(Si ya clonaste el repositorio, simplemente copia estos archivos dentro de tu carpeta clonada y ejecuta `git add .`, `git commit` y `git push`.)*

## Publicar en Firebase Hosting

```bash
npm install -g firebase-tools
firebase login
firebase deploy --only hosting
```

Tu vCard quedará disponible en:
- `https://ciencia1minuto-24f9f.web.app`
- `https://ciencia1minuto-24f9f.firebaseapp.com`
