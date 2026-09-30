# Cartera de ejemplares

Aquí se guardan los 36 números de la revista La Letra.

## Estructura

```
ejemplares/
├── numero-1/
│   ├── portada.jpg
│   └── numero-1.pdf
├── numero-2/
│   ├── portada.jpg
│   └── numero-2.pdf
├── ...
└── numero-36/
    ├── portada.jpg
    └── numero-36.pdf
```

## Cómo se genera

- Cada número se guarda dentro de su propia carpeta `numero-X/`
- La portada debe llamarse `portada.jpg` o `portada.png`
- El PDF debe llamarse `numero-X.pdf`
- La galería principal (`index.html`) lee los datos de `data/issues.json` y genera la galería automáticamente

## Agregar nuevos números

Si necesitas agregar más números en el futuro:

1. Crea una carpeta `numero-37/` (o el que sea)
2. Sube la portada como `portada.jpg`
3. Sube el PDF como `numero-37.pdf`
4. Añade una entrada en `data/issues.json`
