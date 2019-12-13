# DS
Design System


live sass compiler setting : 
```
{
"liveSassCompile.settings.formats": [
    {
      "format": "expanded",
      "extensionName": ".css",
      "savePath": "/css"
    }
  ],
  "liveSassCompile.settings.excludeList": [
    "**/node_modules/**",
    ".vscode/**"
  ],
  "liveSassCompile.settings.generateMap": false,
  "liveSassCompile.settings.autoprefix": [
    "> 1%",
    "last 2 versions"
  ]
}
```
Typography : scss
```
html {
  font-size: 62.5% !important;
  /* -> 10px , 1em , 1rem */
}

body {
  font-size: 1.6rem;
  line-height: 1.4;
}
```
