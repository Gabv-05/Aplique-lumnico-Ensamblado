# Modelo 3D · Aplique lumínico de despertar progresivo

Página estática para GitHub Pages que muestra el aplique en 3D: se puede girar, acercar, simular el ciclo de luz y, en el celular, ponerlo en la pared con realidad aumentada.

## Archivos

```
index.html   ← la página
modelo.glb   ← el modelo 3D (ya convertido desde Ensamble_Aplique.stl)
```

Los dos tienen que ir juntos en la misma carpeta.

## Subirlo a GitHub Pages

1. Crea un repositorio nuevo (por ejemplo `aplique-luminico`).
2. Sube `index.html` y `modelo.glb` a la raíz.
3. Ve a **Settings › Pages**, en *Source* elige la rama `main` y la carpeta `/ (root)`, y guarda.
4. En uno o dos minutos queda en `https://TU-USUARIO.github.io/aplique-luminico/`.

## Probarlo antes de subirlo

Si abres `index.html` con doble clic, el navegador no deja cargar `modelo.glb` desde el disco: la página mostrará un recuadro donde puedes **arrastrar el .glb** para verlo. En GitHub Pages carga solo.

## Cambiar el modelo

Si actualizas el diseño, exporta de nuevo como `.glb` (en Blender: Archivo › Exportar › glTF 2.0 › *glTF Binary*) y reemplaza `modelo.glb` con el mismo nombre. Desde Inventor, exporta a `.stl` u `.obj`, ábrelo en Blender y expórtalo como `.glb`.
