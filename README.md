# Portafolio personal

Frontend de página web de Nelson Galicia Carrero.

Sitio publicado: https://pistachopower.github.io/Construccion_Portafolio/


## Probar en local

Este proyecto es estático y no necesita instalar dependencias.

1. Clona el repositorio y entra en su carpeta:

	```bash
	git clone https://github.com/Pistachopower/Construccion_Portafolio.git
	cd Construccion_Portafolio
	```

2. Inicia un servidor local desde la raíz del proyecto:

	```bash
	python3 -m http.server 8000
	```

3. Abre http://localhost:8000 en el navegador.

Para detener el servidor, pulsa `Ctrl+C` en la terminal.

## Publicar en GitHub Pages

El workflow de GitHub Actions publica automáticamente el contenido de la rama
`main` en GitHub Pages después de cada `push`.

Después de realizar cambios:

```bash
git add .
git commit -m "Actualiza el portafolio"
git push origin main
```

GitHub Pages actualizará el sitio en unos instantes en el enlace publicado.
