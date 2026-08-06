# Security Writeups — sitio estático

Sitio simple en HTML/CSS puro (sin frameworks, sin build step) para publicar writeups de CTFs, TryHackMe, pentesting labs, etc.

## Estructura

```
.
├── index.html                  ← página principal (índice de casos)
├── assets/
│   └── style.css                ← toda la identidad visual del sitio
└── writeups/
    ├── template.html            ← plantilla en blanco, copiar para cada writeup nuevo
    └── example-byte-lotus.html  ← ejemplo relleno, borrar cuando ya no lo necesites
```

