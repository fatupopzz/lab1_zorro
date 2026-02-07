# La Odisea del Zorro

Un juego interactivo de "elige tu propia aventura" siguiendo el viaje de un zorro a través de tierras misteriosas. Hecho con HTML puro, sin CSS ni JavaScript.

## Estructura del proyecto
- `inicio/` - Punto de partida (index.html)
- `capitulos/` - Capítulos de la historia con decisiones
- `finales/` - Tres finales diferentes (bueno, neutro, malo)
- `imagenes/` - Todas las imágenes usadas en el juego


## Cómo ejecutar el juego

### Localmente
Abre `inicio/index.html` en tu navegador

### Con NGINX
1. Copia los archivos al directorio de NGINX:
```bash
   sudo cp -r * /var/www/html/odisea-del-zorro/
```

2. Establece los permisos:
```bash
   sudo chmod -R 755 /var/www/html/odisea-del-zorro
```

3. Accede desde el navegador:
```
   http://localhost/odisea-del-zorro/inicio/
```

